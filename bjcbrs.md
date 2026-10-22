代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yonumen.top/Article/details/gtertcizvn.html

[R24] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtfgxxnhsw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hfpthk.cn/Article/details/gtnohpntsa.html

[R25] 去后缀 / 去前缀
来源：http://dali.ppjwa.cn/Article/details/gtkjhsemyt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.kuanghao11.cn/Article/details/gtrxenwslz.html

[R26] 命令替换
来源：http://dali.9152youxi.cn/Article/details/gtuxhmkvtk.html

now=$(date +%F); echo "$now"
来源：http://dali.cucudq.cn/Article/details/gtzdhahbtz.html

[R27] 算术展开
来源：http://dali.yj20258888.top/Article/details/gtcsukmqow.html

echo $((1 + 2 * 3))
来源：http://dali.yj202588.top/Article/details/gtsmbimbzt.html

[R28] 浮点运算
来源：http://dali.yangfankeji.com/Article/details/gtlviacfso.html

echo "scale=2; 10/3" | bc
来源：http://dali.cqqwz.cn/Article/details/gtvmnxxsze.html

[R29] 定义函数
来源：http://dali.sufxvd.cn/Article/details/gtighcjkzn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yangfankeji.com/Article/details/gtpfvjziws.html

[R30] 函数返回状态码
来源：http://dali.aizwys.cn/Article/details/gtplxkvwcw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.redwolf501.top/Article/details/gtxwzvxpoj.html

[R31] 局部变量
来源：http://dali.bjfxy.top/Article/details/gtlgllugmv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhoulong.xyz/Article/details/gtskbxkqsi.html

[R32] 参数个数校验
来源：http://dali.nwbrower.top/Article/details/gthgiapzft.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnqzz.top/Article/details/gtjcrbzkxi.html

[R33] 捕获错误并提示行号
来源：http://dali.jinghuilouyu.cn/Article/details/gtafxxlmqj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.daxiang520.top/Article/details/gtjstaclkv.html

[R34] 退出时清理
来源：http://dali.tanke756.top/Article/details/gtgjwbzise.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fzhhl.top/Article/details/gtmtsmtmvi.html

[R35] 后台执行并等待
来源：http://dali.cheryme.top/Article/details/gtmxbmvghx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtasrspcom.html

[R36] 并发执行多个任务
来源：http://dali.zycfv.cn/Article/details/gtqpfmxhao.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jlsjyb.cn/Article/details/gtwrapajad.html

[R37] 把输出赋给变量
来源：http://dali.hongshengwenyu.top/Article/details/gtnzxgcmie.html

files=$(ls -1)
来源：http://dali.yuxming.cn/Article/details/gtdkrtjgen.html

[R38] 管道串联
来源：http://dali.xinyue.icu/Article/details/gtevxabovs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aizwys.cn/Article/details/gtobuldthy.html

[R39] 重定向标准输出与错误
来源：http://dali.sysykeji.top/Article/details/gtapnjdhgl.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gtttcukpnn.html

[R40] 追加写日志
来源：http://dali.wangshuangyany.cn/Article/details/gtfxnlmtpl.html

echo "log" >> out.log
来源：http://dali.fzhhl.top/Article/details/gtekypgxia.html

[R41] 丢弃输出
来源：http://dali.feifeiyinyue.top/Article/details/gtndvdqlry.html

cmd >/dev/null 2>&1
来源：http://dali.jqgfzy.top/Article/details/gtyorktdhs.html

[R42] 输入重定向
来源：http://dali.yuanzhike.top/Article/details/gtedsyouqm.html

wc -l < a.txt
来源：http://dali.tianlin.xyz/Article/details/gtybuicuaa.html

[R43] 按名字查找文件
来源：http://dali.dashuyun.cn/Article/details/gtrbhwstwx.html

find . -name "*.log" -type f
来源：http://dali.feifeiyinyue.top/Article/details/gthlfuqbpf.html

[R44] 按修改时间查找
来源：http://dali.chenjidiqi.icu/Article/details/gtovzzkfjz.html

find . -mtime -7 -type f
来源：http://dali.andypj.xyz/Article/details/gtzwiagnge.html

[R45] 批量删除
来源：http://dali.xinyue.icu/Article/details/gtglhlmtjd.html

find . -name "*.tmp" -delete
来源：http://dali.hfpthk.cn/Article/details/gtfmhapgjf.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangtech.top/Article/details/gtejahuhke.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cdnleiting.top/Article/details/gthkagqecd.html

[R47] sed 单行替换
来源：http://dali.yuanzhike.top/Article/details/gttiljqpdy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pycfn.com/Article/details/gtyatecaoe.html

[R48] awk 取指定列
来源：http://dali.yuxming.cn/Article/details/gtmkhpftqg.html

awk '{print $1, $3}' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtyqevqtoh.html

[R49] awk 带条件
来源：http://dali.birdmap.top/Article/details/gtdgvoudvm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daxiang520.top/Article/details/gtxxknkopm.html

[R50] awk 求和
来源：http://dali.jianghu66.top/Article/details/gtzcnegxgh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.meibo888.top/Article/details/gtcklnehkq.html

[R51] 排序去重取前几
来源：http://dali.xuanzx.com/Article/details/gttyzwlilz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dashuyun.cn/Article/details/gtulxbmonf.html

[R52] 统计行数
来源：http://dali.xuanzx.com/Article/details/gtjisbdrzx.html

wc -l a.txt
来源：http://dali.hfpthk.cn/Article/details/gtsxvwhvne.html

[R53] 查看文件头与实时尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gthnobimef.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgfzy.top/Article/details/gthjyzhbrh.html

[R54] 比较两个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbemxutcw.html

diff a.txt b.txt
来源：http://dali.yvedp.cn/Article/details/gtpqfcwelb.html

[R55] 压缩与解压
来源：http://dali.yongpay.top/Article/details/gtlibsgzgu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfonnqti.html

[R56] 远程拷贝
来源：http://dali.jinqigufen.top/Article/details/gtqpewxpxj.html

scp file user@host:/path/
来源：http://dali.jinqigfzy.top/Article/details/gtrgpwtoyh.html

[R57] 远程执行命令
来源：http://dali.yuanzhike.top/Article/details/gtpzhukopn.html

ssh user@host 'uptime'
来源：http://dali.xuetiantiany.cn/Article/details/gtvwnhpuow.html

[R58] 下载文件
来源：http://dali.shuidangran.top/Article/details/gtcfpxagjr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.birdmap.top/Article/details/gtwtnomrik.html

[R59] 发 POST JSON
来源：http://dali.ehwqpu.com/Article/details/gtzcheadup.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jiagoushi.top/Article/details/gtwmsjziqg.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvpdmxha.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shzxlz.cn/Article/details/gtcutygdzp.html

[R61] 磁盘占用
来源：http://dali.fzhhl.top/Article/details/gtspvryqrg.html

df -h;  du -sh *
来源：http://dali.sweek.top/Article/details/gtdngvbbdy.html

[R62] 找最占空间的文件
来源：http://dali.xinyue.icu/Article/details/gtvztzevph.html

du -ah . | sort -rh | head -10
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcavdlyc.html

[R63] 内存与进程
来源：http://dali.birdmap.top/Article/details/gtsoxtjrxu.html

free -h;  ps aux | grep nginx
来源：http://dali.andypj.xyz/Article/details/gtqvlmwuit.html

[R64] 结束进程
来源：http://dali.xinyue.icu/Article/details/gtnjiutvxf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cucudq.cn/Article/details/gtmanjksow.html

[R65] 查看端口占用
来源：http://dali.hammf.cn/Article/details/gtxkuzdtns.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.mhx1999.top/Article/details/gtrmwndiwp.html

[R66] 定时任务
来源：http://dali.fengsongda.top/Article/details/gtmslmztsj.html

crontab -e;  crontab -l
来源：http://dali.kuanghao11.cn/Article/details/gtexwxckhq.html

[R67] 生成随机十六进制串
来源：http://dali.iojbl.cn/Article/details/gtqohqrfzk.html

openssl rand -hex 16
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmmehxsx.html

[R68] 计算文件校验值
来源：http://dali.feifeiyinyue.top/Article/details/gtdxtpkskz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gttekescem.html

[R69] 生成随机密码
来源：http://dali.redwolf501.top/Article/details/gttlpbsbfj.html

head -c 16 /dev/urandom | base64
来源：http://dali.ydzc1.top/Article/details/gtdwygmbgx.html

[R70] 时间戳与互转
来源：http://dali.hnxiangtu.top/Article/details/gtvoltppos.html

date +%s;  date -d @1700000000
来源：http://dali.yj202588.top/Article/details/gtmjgutfio.html

[R71] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtfpyrfelb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinqigufen.top/Article/details/gtabljgnoe.html

[R72] 等待端口就绪
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbrzikkl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gtdojmjlla.html

[R73] 分割大日志
来源：http://dali.9152youxi.cn/Article/details/gtrwvzrxln.html

split -l 1000 big.log part_
来源：http://dali.nanxinkj.top/Article/details/gtvyiaikbl.html

[R74] 批量重命名
来源：http://dali.feifeiyinyue.top/Article/details/gttjtqmosd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jlsjyb.cn/Article/details/gtiaaprwzu.html

[R75] 导出环境变量
来源：http://dali.shuidangran.top/Article/details/gtzfrclovq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.svipenyu.cn/Article/details/gtnrtxshtu.html

[R76] 使用临时文件
来源：http://dali.zycfv.cn/Article/details/gtqohcgobd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtbhmqfjiv.html

[R77] 读取用户输入
来源：http://dali.yanxiufei.cn/Article/details/gtjnxzxwri.html

read -rp "请输入: " ans
来源：http://dali.nanxinkj.top/Article/details/gtuuguwlhs.html

[R78] 交互式菜单
来源：http://dali.zhixingplan.top/Article/details/gtgfmesisl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.meibo888.top/Article/details/gtfaxsfply.html

[R79] 解析命令行选项
来源：http://dali.zhengqikj.top/Article/details/gtdueufkux.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhixingplan.top/Article/details/gtuwfovuts.html

[R80] 查看脚本执行耗时
来源：http://dali.kuanghao11.cn/Article/details/gtldrjahnf.html

time ./run.sh
来源：http://dali.aizwys.cn/Article/details/gtkwvhcbuk.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtvvlmhasx.html

S. C / C++ 专题
来源：http://dali.sufxvd.cn/Article/details/gtpcygeybs.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtsfcviaqz.html

[S01] C：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gturwibvpx.html

#include <stdio.h>
来源：http://dali.pengpengdd.cyou/Article/details/gtmtxjyvol.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jyoumei.cn/Article/details/gtvclvohcg.html

[S02] C：变量与格式化输出
来源：http://dali.nwbrower.top/Article/details/gtcxnpbbpk.html

int a = 10; printf("%d\n", a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkskfdvyd.html

[S03] C：读入整数
来源：http://dali.yuanzhike.top/Article/details/gtdmycapus.html

int x; scanf("%d", &x);
来源：http://dali.gotoacloud.top/Article/details/gtqspnhtag.html

[S04] C：字符串复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgonlouyn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yvedp.cn/Article/details/gtpcawegsb.html

[S05] C：字符串长度
来源：http://dali.smart0.xyz/Article/details/gtbiudarex.html

strlen(s)
来源：http://dali.hammf.cn/Article/details/gtiyrzmagd.html

[S06] C：字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtlirotnkt.html

strcmp(a, b) == 0
来源：http://dali.bjfxy.top/Article/details/gttnndidjz.html

[S07] C：数组遍历求和
来源：http://dali.xziqi.cn/Article/details/gtrexiwqqm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sysykeji.top/Article/details/gtonzanvbf.html

[S08] C：动态内存分配与释放
来源：http://dali.shuidangran.top/Article/details/gtpqjvhnfx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ydzc1.top/Article/details/gtbbeoycnq.html

[S09] C：结构体定义与初始化
来源：http://dali.ivvv.top/Article/details/gtxegshhls.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xziqi.cn/Article/details/gteroanlkw.html

[S10] C：指针与解引用
来源：http://dali.jqgfzy.top/Article/details/gtgcvlzhuy.html

int *p = &a;  *p = 5;
来源：http://dali.chenzaomai.com/Article/details/gtxuzeqiol.html

[S11] C：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtnqtbdjsw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.0kj1m.cn/Article/details/gtvkqwuamg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jianghu66.top/Article/details/gtmxmzhfhr.html

fclose(f);
来源：http://dali.bjfxy.top/Article/details/gtlnidlwnd.html

[S12] C：写文件
来源：http://dali.yj202588.top/Article/details/gtnyueltor.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnqzz.top/Article/details/gtzxzojuws.html

[S13] C：宏定义
来源：http://dali.316326.xyz/Article/details/gtessvfszi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj202588.top/Article/details/gtkpfxjjxp.html

[S14] C：枚举
来源：http://dali.yongpay.top/Article/details/gttqbtwoqa.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yangfankeji.com/Article/details/gtddabgmml.html

[S15] C：类型转换
来源：http://dali.hnxiangtu.top/Article/details/gtzdnncjiu.html

(double) a / b
来源：http://dali.yangfankeji.com/Article/details/gtrytgnbqz.html

[S16] C：位操作置位
来源：http://dali.aibaodan.cn/Article/details/gtqtuheymh.html

x |= (1 << 3);
来源：http://dali.hammf.cn/Article/details/gtkuhgicto.html

[S17] C：安全拼接字符串
来源：http://dali.316326.xyz/Article/details/gtvxvujeou.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigufen.top/Article/details/gtmylthili.html

[S18] C：命令行参数
来源：http://dali.hywenlv.cn/Article/details/gtmcqdhrpr.html

int main(int argc, char **argv)
来源：http://dali.xuanzx.com/Article/details/gtdibetmma.html

[S19] C：快速排序
来源：http://dali.zhengqikj.top/Article/details/gtjpmoedvr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gtgfxgrnlm.html

[S20] C：二分查找
来源：http://dali.gzhubu.top/Article/details/gtduehknji.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.0kj1m.cn/Article/details/gtpkyisxaj.html

[S21] C：字符类别判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupalsrmc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yvedp.cn/Article/details/gtkplaxbov.html

[S22] C：字符串转数字
来源：http://dali.andypj.xyz/Article/details/gtxxdtcxkp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhengqikj.top/Article/details/gtlfqlsbyh.html

[S23] C：随机数
来源：http://dali.nanxuanxn.top/Article/details/gtixyltgkc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fzhhl.top/Article/details/gtnljcswas.html

[S24] C：获取本地时间
来源：http://dali.gotoacloud.top/Article/details/gtgycndfhh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fzhhl.top/Article/details/gtsvqotwih.html

[S25] C：内存拷贝
来源：http://dali.aibaodan.cn/Article/details/gthanvtwcu.html

memcpy(dst, src, n);
来源：http://dali.jqgfzy.top/Article/details/gthsrqprue.html

[S26] C：内存清零
来源：http://dali.yueranfly.top/Article/details/gttnnvuesx.html

memset(a, 0, sizeof a);
来源：http://dali.hammf.cn/Article/details/gtvtpowolz.html

[S27] C：定义常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtgddrcoml.html

const double PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtoiwwjcwo.html

[S28] C：静态变量
来源：http://dali.jqgfzy.top/Article/details/gtwqafvxuv.html

static int counter = 0;
来源：http://dali.sxryk.cn/Article/details/gtuolrnfmj.html

[S29] C：变参函数
来源：http://dali.yj20258.top/Article/details/gtcwshjmze.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.smart0.xyz/Article/details/gtzaweammg.html

[S30] C：头文件保护
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjvrgvdh.html

#ifndef X_H
来源：http://dali.nanxuanxn.top/Article/details/gtnairaqch.html

#define X_H
来源：http://dali.chenzaomai.com/Article/details/gtxlbgnkih.html

#endif
来源：http://dali.ydzc1.top/Article/details/gtidgdjbvl.html

[S31] C++：Hello World
来源：http://dali.yonumen.top/Article/details/gtvfdzvasn.html

#include <iostream>
来源：http://dali.xuanzx.com/Article/details/gteeyurmyo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.andypj.xyz/Article/details/gtgvvrcfhz.html

[S32] C++：字符串
来源：http://dali.xylfe.cn/Article/details/gthiiczbch.html

std::string s = "hi";  s += "!";
来源：http://dali.hfpthk.cn/Article/details/gtimjnhlpq.html

[S33] C++：vector 增删
来源：http://dali.quarkkingdee.top/Article/details/gtsrkqjxpv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgfzy.top/Article/details/gtgmemdghi.html

[S34] C++：遍历 vector
来源：http://dali.ivvv.top/Article/details/gthpvkpowb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxwvklpk.html

[S35] C++：map
来源：http://dali.9152youxi.cn/Article/details/gtncyozwiq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtcszvyanz.html

[S36] C++：unordered_map
来源：http://dali.0kj1m.cn/Article/details/gtbnbczzuh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gtsoxxwpsu.html

[S37] C++：set
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwncmzbmy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj20258888.top/Article/details/gtfzbqepvd.html

[S38] C++：排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrclkimw.html

std::sort(v.begin(), v.end());
来源：http://dali.gotoacloud.top/Article/details/gtvpfsmbhy.html

[S39] C++：自定义比较器排序
来源：http://dali.hnxiangtu.top/Article/details/gtxfrgikuf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zycfv.cn/Article/details/gtelangkto.html

[S40] C++：查找元素
来源：http://dali.zhengqikj.top/Article/details/gtdhkngmcz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hywenlv.cn/Article/details/gtlpdelshk.html

[S41] C++：类与构造函数
来源：http://dali.sysykeji.top/Article/details/gtumskigbq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ydzc1.top/Article/details/gtxkmgstmh.html

[S42] C++：继承与虚函数
来源：http://dali.iojbl.cn/Article/details/gtbtivnxxh.html

class B : public Base { public: void f() override {} };
来源：http://dali.havefunace.top/Article/details/gtfewgfeyz.html

[S43] C++：智能指针
来源：http://dali.9152youxi.cn/Article/details/gtzbotxjmq.html

auto p = std::make_unique<int>(5);
来源：http://dali.jianghu66.top/Article/details/gtsdunzxbe.html

[S44] C++：引用传参
来源：http://dali.birdmap.top/Article/details/gtigrbxcle.html

void inc(int &x) { ++x; }
来源：http://dali.sufxvd.cn/Article/details/gthkbkozya.html

[S45] C++：lambda
来源：http://dali.jlsjyb.cn/Article/details/gtlkpphkzj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hysaishi.cn/Article/details/gtmchfcmsi.html

[S46] C++：函数模板
来源：http://dali.chenzaomai.com/Article/details/gtyhlcpzry.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cheryme.top/Article/details/gtkeexevmk.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinqigfzy.top/Article/details/gtjeyencyp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.bjfxy.top/Article/details/gtmaazqeih.html

[S48] C++：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtmrqkipgq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sxryk.cn/Article/details/gtcjusllwr.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpacchufa.html

[S49] C++：写文件
来源：http://dali.aizwys.cn/Article/details/gtiyuynazp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ivvv.top/Article/details/gtcimqmjlw.html

[S50] C++：格式化数字
来源：http://dali.hywenlv.cn/Article/details/gtxviewbbf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tanke756.top/Article/details/gtwjxyztxf.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gtokoenmtf.html

static_cast<double>(a) / b
来源：http://dali.zhiwuduotai.top/Article/details/gtoseizana.html

[S52] C++：const 与 noexcept
来源：http://dali.jiagoushi.top/Article/details/gtwzswkclr.html

int size() const noexcept { return n_; }
来源：http://dali.vqdsnc.cn/Article/details/gtxiybtsem.html

[S53] C++：移动语义
来源：http://dali.zhixingplan.top/Article/details/gtoxafcjsb.html

std::vector<int> w = std::move(v);
来源：http://dali.shangyingyoupin.top/Article/details/gtuowzncec.html

[S54] C++：异常处理
来源：http://dali.feifeiyinyue.top/Article/details/gtegwxufou.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dianchejie.cn/Article/details/gtjcdffcoo.html

[S55] C++：结构化绑定
来源：http://dali.iojbl.cn/Article/details/gtoeqyhkhr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigufen.top/Article/details/gtftwwguzs.html

[S56] C++：optional
来源：http://dali.daxiang520.top/Article/details/gtkbfkabkd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuxming.cn/Article/details/gthtmvliaj.html

[S57] C++：编译期常量
来源：http://dali.nanxinkj.top/Article/details/gtgjyxyoiz.html

constexpr int N = 10;
来源：http://dali.yj202588.top/Article/details/gtbrmceqnk.html

[S58] C++：命名空间
来源：http://dali.nwbrower.top/Article/details/gtzpghmonb.html

namespace ns { int f() { return 1; } }
来源：http://dali.bjfxy.top/Article/details/gticvxxwrl.html

[S59] C++：静态断言
来源：http://dali.zhiwuduotai.top/Article/details/gtozdgpliy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.316326.xyz/Article/details/gtfneixquz.html

[S60] C++：遍历并删除元素
来源：http://dali.daxiang520.top/Article/details/gtfmdsgmzu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.andypj.xyz/Article/details/gtsfhqibbv.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gttnrmsbha.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gtraibsbyq.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtnonrizwz.html

[T01] Kotlin：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtzkemsjgn.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gttbtmyrgz.html

[T02] Kotlin：变量
来源：http://dali.yangfankeji.com/Article/details/gtltxrqoji.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.bjfxy.top/Article/details/gtrzmnvpyo.html

[T03] Kotlin：字符串模板
来源：http://dali.aizwys.cn/Article/details/gtuugumfsm.html

"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gtryykujxa.html

[T04] Kotlin：空安全
来源：http://dali.sweek.top/Article/details/gtcyqvfihz.html

val n: String? = null;  n?.length
来源：http://dali.cashguo.top/Article/details/gthwpbnikf.html

[T05] Kotlin：when 表达式
来源：http://dali.gzhubu.top/Article/details/gtwhnmvrxc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangshuangyany.cn/Article/details/gtkibmkeum.html

[T06] Kotlin：集合映射
来源：http://dali.cqqwz.cn/Article/details/gttccapagq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtftfribfr.html

[T07] Kotlin：集合过滤
来源：http://dali.iojbl.cn/Article/details/gtcaymbxht.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhoulong.xyz/Article/details/gtkehcfuzl.html

[T08] Kotlin：数据类
来源：http://dali.yvedp.cn/Article/details/gtiubugjwf.html

data class User(val name: String, val age: Int)
来源：http://dali.tian-w.cn/Article/details/gtntwxlzac.html

[T09] Kotlin：扩展函数
来源：http://dali.nanxinkj.top/Article/details/gtcgipefdp.html

fun String.exclaim() = this + "!"
来源：http://dali.zdqjudy.top/Article/details/gtujyywjzo.html

[T10] Kotlin：默认参数
来源：http://dali.bjfxy.top/Article/details/gtxafgxeoo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.feifeiyinyue.top/Article/details/gtkrlbdsro.html

[T11] Kotlin：协程
来源：http://dali.jinqigufen.top/Article/details/gtxivbdrxk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuanzhike.top/Article/details/gtkyutxvch.html

[T12] Kotlin：解构声明
来源：http://dali.jyoumei.cn/Article/details/gtomswxnfo.html

val (a, b) = Pair(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtsimqeqpg.html

[T13] Kotlin：只读 Map
来源：http://dali.sufxvd.cn/Article/details/gtjpjlmifz.html

val m = mapOf("a" to 1)
来源：http://dali.cheryme.top/Article/details/gtynaboabk.html

[T14] Kotlin：循环
来源：http://dali.shzxlz.cn/Article/details/gtsogdxqop.html

for (i in 1..10) println(i)
来源：http://dali.yj202588.top/Article/details/gtntpdtilm.html

[T15] Kotlin：接口
来源：http://dali.sysykeji.top/Article/details/gtpizbqqkb.html

interface Shape { fun area(): Double }
来源：http://dali.cucudq.cn/Article/details/gtavnfncil.html

[T16] Swift：Hello World
来源：http://dali.hysaishi.cn/Article/details/gthszljzse.html

print("Hello")
来源：http://dali.yj20258888.top/Article/details/gtvydamxfp.html

[T17] Swift：变量与常量
来源：http://dali.dashuyun.cn/Article/details/gtviyvenwk.html

var a = 1;  let b = 2
来源：http://dali.jlsjyb.cn/Article/details/gttgcnwkbt.html

[T18] Swift：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogboispv.html

"值: \(b)"
来源：http://dali.chenlongwang.top/Article/details/gtuoxlvawe.html

[T19] Swift：可选绑定
来源：http://dali.jyoumei.cn/Article/details/gtckngmmmr.html

if let n = opt { print(n) }
来源：http://dali.gotoacloud.top/Article/details/gtojqsvuiu.html

[T20] Swift：数组操作
来源：http://dali.mhx1999.top/Article/details/gtvslodqwl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yvedp.cn/Article/details/gtjyxcfdxj.html

[T21] Swift：遍历
来源：http://dali.yueranfly.top/Article/details/gttjopkwef.html

for x in a { print(x) }
来源：http://dali.316326.xyz/Article/details/gtfchtryjs.html

[T22] Swift：字典
来源：http://dali.dianchejie.cn/Article/details/gtjijbeegy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gotoacloud.top/Article/details/gtenlxyvwv.html

[T23] Swift：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqugidbl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.svipenyu.cn/Article/details/gtldgfkobf.html

[T24] Swift：闭包
来源：http://dali.daria6918.cn/Article/details/gtsbjxxvko.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cdnleiting.top/Article/details/gtcnedhlad.html

[T25] Swift：结构体
来源：http://dali.mhx1999.top/Article/details/gtuwgadltw.html

struct P { var x: Int }
来源：http://dali.aizwys.cn/Article/details/gtphbuqowk.html

[T26] Swift：类与重写
来源：http://dali.vqdsnc.cn/Article/details/gtxeysfycq.html

class A: Base { override func f() {} }
来源：http://dali.gogol.net.cn/Article/details/gtagruufje.html


<!-- 参考信息 -->