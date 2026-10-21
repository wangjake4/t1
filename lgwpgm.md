代发 wailian999

echo "${#s}"
来源：http://dali.sysykeji.top/Article/details/gtsdcrxbxj.html

[R22] 截取子串
来源：http://dali.daxiang520.top/Article/details/gtvmmolbpx.html

echo "${s:0:5}"
来源：http://dali.nwbrower.top/Article/details/gtvqfyhhxw.html

[R23] 字符串替换
来源：http://dali.shuidangran.top/Article/details/gtgsjxbdim.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.kuanghao11.cn/Article/details/gtqahhxdzk.html

[R24] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gtchegwueq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.meibo888.top/Article/details/gtrygvbjnz.html

[R25] 去后缀 / 去前缀
来源：http://dali.nwbrower.top/Article/details/gtevloqggf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhengqikj.top/Article/details/gtnazldhne.html

[R26] 命令替换
来源：http://dali.dianchejie.cn/Article/details/gtlefnkbmn.html

now=$(date +%F); echo "$now"
来源：http://dali.zhoulong.xyz/Article/details/gtmiwbptub.html

[R27] 算术展开
来源：http://dali.jinghuilouyu.cn/Article/details/gtsurtjglp.html

echo $((1 + 2 * 3))
来源：http://dali.xuanzx.com/Article/details/gthhvlglxo.html

[R28] 浮点运算
来源：http://dali.yuxming.cn/Article/details/gtigiwbhww.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gtdrckgkwo.html

[R29] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gthletccif.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.pengpengdd.cyou/Article/details/gtzyhagezt.html

[R30] 函数返回状态码
来源：http://dali.cdnleiting.top/Article/details/gtcvvuveap.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgufenzy.top/Article/details/gtztuqvgeh.html

[R31] 局部变量
来源：http://dali.smart0.xyz/Article/details/gtpujkglci.html

f() { local x=1; echo "$x"; }
来源：http://dali.jlsjyb.cn/Article/details/gtwpfvuwqc.html

[R32] 参数个数校验
来源：http://dali.316326.xyz/Article/details/gtuzlgvotq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gtbtmcxubq.html

[R33] 捕获错误并提示行号
来源：http://dali.hfpthk.cn/Article/details/gtpdysxsua.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xinyue.icu/Article/details/gtqrgfifxj.html

[R34] 退出时清理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyrjxrmb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gtpcaxmrlu.html

[R35] 后台执行并等待
来源：http://dali.yj20258888.top/Article/details/gteyckyemt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj202588.top/Article/details/gtcusjohcx.html

[R36] 并发执行多个任务
来源：http://dali.yonumen.top/Article/details/gtuujknxli.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinqigfzy.top/Article/details/gtygbfgdzm.html

[R37] 把输出赋给变量
来源：http://dali.dianchejie.cn/Article/details/gtspgetkvm.html

files=$(ls -1)
来源：http://dali.zhoulong.xyz/Article/details/gtwgfaltke.html

[R38] 管道串联
来源：http://dali.shuidangran.top/Article/details/gtcvosisdv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shangyingyoupin.top/Article/details/gtbxlnsdtu.html

[R39] 重定向标准输出与错误
来源：http://dali.ybcxt.top/Article/details/gtaphzcraw.html

cmd > out.log 2>&1
来源：http://dali.jyoumei.cn/Article/details/gtynchqove.html

[R40] 追加写日志
来源：http://dali.hnxiangtu.top/Article/details/gtcslhsjxx.html

echo "log" >> out.log
来源：http://dali.daria6918.cn/Article/details/gtvtpexrag.html

[R41] 丢弃输出
来源：http://dali.birdmap.top/Article/details/gtzbizowvv.html

cmd >/dev/null 2>&1
来源：http://dali.sweek.top/Article/details/gterjegtzc.html

[R42] 输入重定向
来源：http://dali.shanyushiyangtech.top/Article/details/gtlrnmwcgf.html

wc -l < a.txt
来源：http://dali.sysykeji.top/Article/details/gtbrssyfcp.html

[R43] 按名字查找文件
来源：http://dali.fzhhl.top/Article/details/gtyovaltzp.html

find . -name "*.log" -type f
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxmgmwjm.html

[R44] 按修改时间查找
来源：http://dali.xuanzx.com/Article/details/gtneksxsom.html

find . -mtime -7 -type f
来源：http://dali.cucudq.cn/Article/details/gtjkhlkqpa.html

[R45] 批量删除
来源：http://dali.jinqigufen.top/Article/details/gtinapcgxm.html

find . -name "*.tmp" -delete
来源：http://dali.zhengqikj.top/Article/details/gteggcfems.html

[R46] 递归替换文件内容
来源：http://dali.cheryme.top/Article/details/gttebqqqky.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yonumen.top/Article/details/gtnveftvrj.html

[R47] sed 单行替换
来源：http://dali.zycfv.cn/Article/details/gtyurxdeup.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtwswtlhpu.html

[R48] awk 取指定列
来源：http://dali.yvedp.cn/Article/details/gtsxfhewtb.html

awk '{print $1, $3}' a.txt
来源：http://dali.yuxming.cn/Article/details/gtxkqowffc.html

[R49] awk 带条件
来源：http://dali.guannengcc.top/Article/details/gtzbdvsnya.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.redwolf501.top/Article/details/gtalfydjce.html

[R50] awk 求和
来源：http://dali.nanxinkj.top/Article/details/gtxronnmuo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtbxrfsbec.html

[R51] 排序去重取前几
来源：http://dali.smart0.xyz/Article/details/gttxrooido.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hongshengwenyu.top/Article/details/gtjeaxlwiy.html

[R52] 统计行数
来源：http://dali.gaohongyu789.top/Article/details/gtfinovrkp.html

wc -l a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtgoykqnbz.html

[R53] 查看文件头与实时尾
来源：http://dali.yongpay.top/Article/details/gtbzgwgnof.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujqyzejb.html

[R54] 比较两个文件
来源：http://dali.guowangkeji.top/Article/details/gtgvfpykdn.html

diff a.txt b.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtydfjxw.html

[R55] 压缩与解压
来源：http://dali.guannengcc.top/Article/details/gtdxeechpc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhoulong.xyz/Article/details/gtaxscvqih.html

[R56] 远程拷贝
来源：http://dali.vqdsnc.cn/Article/details/gtjzudtlbf.html

scp file user@host:/path/
来源：http://dali.chenlongwang.top/Article/details/gtizyupbyp.html

[R57] 远程执行命令
来源：http://dali.0kj1m.cn/Article/details/gtinzvhycv.html

ssh user@host 'uptime'
来源：http://dali.aibaodan.cn/Article/details/gtmkchdopi.html

[R58] 下载文件
来源：http://dali.yvedp.cn/Article/details/gtbqtjbnvu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gzhubu.top/Article/details/gtsksiclml.html

[R59] 发 POST JSON
来源：http://dali.hnqzz.top/Article/details/gtlngbtpgo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jianghu66.top/Article/details/gtinxjyljd.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gtjffrxmjh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cashguo.top/Article/details/gtzxthrqnl.html

[R61] 磁盘占用
来源：http://dali.hfpthk.cn/Article/details/gtvwbkzuxz.html

df -h;  du -sh *
来源：http://dali.pengpengdd.cyou/Article/details/gtvfwwuuht.html

[R62] 找最占空间的文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodaucybd.html

du -ah . | sort -rh | head -10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbivwxkk.html

[R63] 内存与进程
来源：http://dali.9152youxi.cn/Article/details/gtnhxsmjln.html

free -h;  ps aux | grep nginx
来源：http://dali.shzxlz.cn/Article/details/gttowpzocv.html

[R64] 结束进程
来源：http://dali.hywenlv.cn/Article/details/gtwhpfjibm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sweek.top/Article/details/gtoabqbcra.html

[R65] 查看端口占用
来源：http://dali.hammf.cn/Article/details/gtpyeiydcp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxohgiwru.html

[R66] 定时任务
来源：http://dali.jinqigfzy.top/Article/details/gtwysihdwy.html

crontab -e;  crontab -l
来源：http://dali.gzhubu.top/Article/details/gtzijqcpcf.html

[R67] 生成随机十六进制串
来源：http://dali.zhixingplan.top/Article/details/gtwyxfulhg.html

openssl rand -hex 16
来源：http://dali.zhiwuduotai.top/Article/details/gtntcewsxg.html

[R68] 计算文件校验值
来源：http://dali.aizwys.cn/Article/details/gtqbdxwjhh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigufen.top/Article/details/gtmydlxgdz.html

[R69] 生成随机密码
来源：http://dali.yj20258.top/Article/details/gtwocxvied.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuanzhike.top/Article/details/gtzpvfgkpt.html

[R70] 时间戳与互转
来源：http://dali.zhiwuduotai.top/Article/details/gtkegbuqdc.html

date +%s;  date -d @1700000000
来源：http://dali.yvedp.cn/Article/details/gtyiggaowd.html

[R71] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gtxjldnamb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yanxiufei.cn/Article/details/gtakghwbfw.html

[R72] 等待端口就绪
来源：http://dali.daria6918.cn/Article/details/gtfsdlbxnp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gtqhckonlt.html

[R73] 分割大日志
来源：http://dali.quarkkingdee.top/Article/details/gtirjaexbk.html

split -l 1000 big.log part_
来源：http://dali.aizwys.cn/Article/details/gtkpsbredu.html

[R74] 批量重命名
来源：http://dali.zycfv.cn/Article/details/gtwvzxmyeu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtrmizfnfk.html

[R75] 导出环境变量
来源：http://dali.xziqi.cn/Article/details/gtjdfysnuu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nanxuanxn.top/Article/details/gtjjbwzped.html

[R76] 使用临时文件
来源：http://dali.smart0.xyz/Article/details/gtftlllvks.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbmqwpmj.html

[R77] 读取用户输入
来源：http://dali.316326.xyz/Article/details/gtpkvzkmvi.html

read -rp "请输入: " ans
来源：http://dali.cqqwz.cn/Article/details/gtsirhqsgz.html

[R78] 交互式菜单
来源：http://dali.yanxiufei.cn/Article/details/gtrsxfxsby.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenjidiqi.icu/Article/details/gtwdzmaajt.html

[R79] 解析命令行选项
来源：http://dali.iojbl.cn/Article/details/gtydijhqvs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj202588.top/Article/details/gtvmphhrun.html

[R80] 查看脚本执行耗时
来源：http://dali.ehwqpu.com/Article/details/gtryaarmiq.html

time ./run.sh
来源：http://dali.hywenlv.cn/Article/details/gtipulafhw.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtpfvxfbom.html

S. C / C++ 专题
来源：http://dali.feifeiyinyue.top/Article/details/gtkoglnvdp.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtsbqrorqo.html

[S01] C：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtlfigbjld.html

#include <stdio.h>
来源：http://dali.dianchejie.cn/Article/details/gtlvmiwcbg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ybcxt.top/Article/details/gtgsboalwj.html

[S02] C：变量与格式化输出
来源：http://dali.yonumen.top/Article/details/gtkxkgiihx.html

int a = 10; printf("%d\n", a);
来源：http://dali.haohaochexian.top/Article/details/gtaicibutj.html

[S03] C：读入整数
来源：http://dali.fengsongda.top/Article/details/gtwddkbcgr.html

int x; scanf("%d", &x);
来源：http://dali.shangyingyoupin.top/Article/details/gtzhckytrg.html

[S04] C：字符串复制
来源：http://dali.shuidangran.top/Article/details/gtkkmjplks.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnqzz.top/Article/details/gtlszyyfcj.html

[S05] C：字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gtivsfxxgh.html

strlen(s)
来源：http://dali.birdmap.top/Article/details/gtkonvoxrp.html

[S06] C：字符串比较
来源：http://dali.tian-w.cn/Article/details/gttsbkhfcb.html

strcmp(a, b) == 0
来源：http://dali.ydzc1.top/Article/details/gthyjrxnvs.html

[S07] C：数组遍历求和
来源：http://dali.hfpthk.cn/Article/details/gtsuxlqhag.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigfzy.top/Article/details/gtgczifasp.html

[S08] C：动态内存分配与释放
来源：http://dali.hysaishi.cn/Article/details/gtyidwnayx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daria6918.cn/Article/details/gtfchnlbns.html

[S09] C：结构体定义与初始化
来源：http://dali.sysykeji.top/Article/details/gtjdniylqq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.snrcjt.cn/Article/details/gtultsotaz.html

[S10] C：指针与解引用
来源：http://dali.cheryme.top/Article/details/gtczrgxgyb.html

int *p = &a;  *p = 5;
来源：http://dali.guowangkeji.top/Article/details/gtqgcragmu.html

[S11] C：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtvngiewwt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fzhhl.top/Article/details/gthrvwaokf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmuouuvvn.html

fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gtdhuynlhr.html

[S12] C：写文件
来源：http://dali.yangfankeji.com/Article/details/gtrlnmjqus.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gtgicxnvkq.html

[S13] C：宏定义
来源：http://dali.jinqigfzy.top/Article/details/gtgvouqifv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pycfn.com/Article/details/gtgivapekl.html

[S14] C：枚举
来源：http://dali.yueranfly.top/Article/details/gtpusulier.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ydzc1.top/Article/details/gtesfnvxqm.html

[S15] C：类型转换
来源：http://dali.snrcjt.cn/Article/details/gtwokxqjbt.html

(double) a / b
来源：http://dali.xylfe.cn/Article/details/gtbpebxqnr.html

[S16] C：位操作置位
来源：http://dali.sweek.top/Article/details/gtkfdyzwuy.html

x |= (1 << 3);
来源：http://dali.wangdashe.top/Article/details/gtgdbsbdah.html

[S17] C：安全拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtoszswttw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.316326.xyz/Article/details/gtldccvgzp.html

[S18] C：命令行参数
来源：http://dali.bjfxy.top/Article/details/gtobkmjklo.html

int main(int argc, char **argv)
来源：http://dali.sxryk.cn/Article/details/gtparhmxhk.html

[S19] C：快速排序
来源：http://dali.316326.xyz/Article/details/gtnoqopqrp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gtanfhtwqu.html

[S20] C：二分查找
来源：http://dali.zhongyouzk.top/Article/details/gtinwasouc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gtcwhcyjso.html

[S21] C：字符类别判断
来源：http://dali.ppjwa.cn/Article/details/gtpfelepdl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xylfe.cn/Article/details/gtesfqirko.html

[S22] C：字符串转数字
来源：http://dali.birdmap.top/Article/details/gtlstymqrb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpurmeop.html

[S23] C：随机数
来源：http://dali.yvedp.cn/Article/details/gtiqzwtxad.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.svipenyu.cn/Article/details/gtkivkysop.html

[S24] C：获取本地时间
来源：http://dali.sysykeji.top/Article/details/gtqulgelaw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhiwuduotai.top/Article/details/gtlyxjwmyi.html

[S25] C：内存拷贝
来源：http://dali.jiagoushi.top/Article/details/gthewmhypi.html

memcpy(dst, src, n);
来源：http://dali.yangfankeji.com/Article/details/gtxanawnnc.html

[S26] C：内存清零
来源：http://dali.zhoulong.xyz/Article/details/gtravxyxgm.html

memset(a, 0, sizeof a);
来源：http://dali.birdmap.top/Article/details/gtaztgmqxg.html

[S27] C：定义常量
来源：http://dali.jqgufenzy.top/Article/details/gtsepjwdlu.html

const double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gthqxcaidx.html

[S28] C：静态变量
来源：http://dali.wangdashe.top/Article/details/gtqallvtky.html

static int counter = 0;
来源：http://dali.316326.xyz/Article/details/gtapnidjlo.html

[S29] C：变参函数
来源：http://dali.ppjwa.cn/Article/details/gtkefezdks.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jianghu66.top/Article/details/gtpdfuuezv.html

[S30] C：头文件保护
来源：http://dali.nanxinkj.top/Article/details/gttdmgmpfu.html

#ifndef X_H
来源：http://dali.xziqi.cn/Article/details/gtrycezqzg.html

#define X_H
来源：http://dali.ivvv.top/Article/details/gtgaqezmym.html

#endif
来源：http://dali.meibo888.top/Article/details/gthafmmkub.html

[S31] C++：Hello World
来源：http://dali.sxryk.cn/Article/details/gthtmrtloz.html

#include <iostream>
来源：http://dali.tanke756.top/Article/details/gtxtvkspxr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yangfankeji.com/Article/details/gttprkzywk.html

[S32] C++：字符串
来源：http://dali.xinyue.icu/Article/details/gtwrjiemik.html

std::string s = "hi";  s += "!";
来源：http://dali.xziqi.cn/Article/details/gtzhgztift.html

[S33] C++：vector 增删
来源：http://dali.shangyingyoupin.top/Article/details/gtjtnrqicw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtwzmafinu.html

[S34] C++：遍历 vector
来源：http://dali.zhongyouzk.top/Article/details/gtwpqanije.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258.top/Article/details/gthbljlxxd.html

[S35] C++：map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbiuwplrz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtevehmoms.html

[S36] C++：unordered_map
来源：http://dali.gogol.net.cn/Article/details/gtbmdtnxav.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gtpmurxkid.html

[S37] C++：set
来源：http://dali.xinyue.icu/Article/details/gtyusjugih.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zycfv.cn/Article/details/gtqkbfeiuf.html

[S38] C++：排序
来源：http://dali.tanke756.top/Article/details/gtyuyftxmf.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gtrplpzxae.html

[S39] C++：自定义比较器排序
来源：http://dali.xziqi.cn/Article/details/gtgveslqmd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gotoacloud.top/Article/details/gtzrnrsnih.html

[S40] C++：查找元素
来源：http://dali.nanxinkj.top/Article/details/gtwejyqhvf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtcafijvuf.html

[S41] C++：类与构造函数
来源：http://dali.xinyue.icu/Article/details/gtuyphnebk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinghuilouyu.cn/Article/details/gttkmonhqx.html

[S42] C++：继承与虚函数
来源：http://dali.cdnleiting.top/Article/details/gtdswupbxp.html

class B : public Base { public: void f() override {} };
来源：http://dali.snrcjt.cn/Article/details/gthyvpwnli.html

[S43] C++：智能指针
来源：http://dali.andypj.xyz/Article/details/gttrytffxm.html

auto p = std::make_unique<int>(5);
来源：http://dali.aizwys.cn/Article/details/gtrxmbqpxk.html

[S44] C++：引用传参
来源：http://dali.haohaochexian.top/Article/details/gtcmrlouns.html

void inc(int &x) { ++x; }
来源：http://dali.meibo888.top/Article/details/gtrudsmell.html

[S45] C++：lambda
来源：http://dali.xuanzx.com/Article/details/gtgnomxwgp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xinyue.icu/Article/details/gtsigdjeqd.html

[S46] C++：函数模板
来源：http://dali.xylfe.cn/Article/details/gtpyhgbkue.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fengsongda.top/Article/details/gtcalnavei.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenzaomai.com/Article/details/gtxibuuxpo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangdashe.top/Article/details/gtarvotakw.html

[S48] C++：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtncxkkdlk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nwbrower.top/Article/details/gtogcsyxod.html

while (std::getline(in, line)) { }
来源：http://dali.kuanghao11.cn/Article/details/gtvqcttmgm.html

[S49] C++：写文件
来源：http://dali.smart0.xyz/Article/details/gtnzyepyvm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenjidiqi.icu/Article/details/gtyjwpktfp.html

[S50] C++：格式化数字
来源：http://dali.havefunace.top/Article/details/gtfknlokqu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoyovdxwy.html

[S51] C++：显式类型转换
来源：http://dali.meibo888.top/Article/details/gtreqcqhqh.html

static_cast<double>(a) / b
来源：http://dali.nwbrower.top/Article/details/gtmzmelspz.html

[S52] C++：const 与 noexcept
来源：http://dali.shzxlz.cn/Article/details/gtbejspkua.html

int size() const noexcept { return n_; }
来源：http://dali.ybcxt.top/Article/details/gtdaxqnlam.html

[S53] C++：移动语义
来源：http://dali.nwbrower.top/Article/details/gtuodvpxge.html

std::vector<int> w = std::move(v);
来源：http://dali.zdqjudy.top/Article/details/gtulrancja.html

[S54] C++：异常处理
来源：http://dali.pycfn.com/Article/details/gtmvpjptto.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlezthejy.html

[S55] C++：结构化绑定
来源：http://dali.aizwys.cn/Article/details/gtbfardadp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhixingplan.top/Article/details/gtkhjykcej.html

[S56] C++：optional
来源：http://dali.cheryme.top/Article/details/gttstvbdiy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tanke756.top/Article/details/gtfqqlpzmd.html

[S57] C++：编译期常量
来源：http://dali.wangshuangyany.cn/Article/details/gtrjxcsqrr.html

constexpr int N = 10;
来源：http://dali.gzhubu.top/Article/details/gtczscjtet.html

[S58] C++：命名空间
来源：http://dali.meibo888.top/Article/details/gtipdlfawb.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuxming.cn/Article/details/gtjzergwek.html

[S59] C++：静态断言
来源：http://dali.yanxiufei.cn/Article/details/gtvpqhofzp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tanke756.top/Article/details/gtplenrzvn.html

[S60] C++：遍历并删除元素
来源：http://dali.pycfn.com/Article/details/gtkwvnxbwz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jianghu66.top/Article/details/gtfgzfvobd.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtpwskmpgx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.mhx1999.top/Article/details/gtywufuobu.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtlnnasayh.html

[T01] Kotlin：Hello World
来源：http://dali.cashguo.top/Article/details/gthgiaybxg.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gtcbdvxkxd.html

[T02] Kotlin：变量
来源：http://dali.iojbl.cn/Article/details/gtjpgbgwkb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.snrcjt.cn/Article/details/gtkvlbwhxm.html

[T03] Kotlin：字符串模板
来源：http://dali.nanxuanxn.top/Article/details/gtbbpnrqcp.html

"值: $b"
来源：http://dali.nwbrower.top/Article/details/gtzaxmssjr.html

[T04] Kotlin：空安全
来源：http://dali.316326.xyz/Article/details/gtxwinyrjq.html

val n: String? = null;  n?.length
来源：http://dali.hnqzz.top/Article/details/gtrmsemlkf.html

[T05] Kotlin：when 表达式
来源：http://dali.iojbl.cn/Article/details/gtmxlomkhq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yongpay.top/Article/details/gtwzhjslkz.html

[T06] Kotlin：集合映射
来源：http://dali.fzhhl.top/Article/details/gtnieqogqk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtjglptmzu.html

[T07] Kotlin：集合过滤
来源：http://dali.guowangkeji.top/Article/details/gtewxezgfa.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjhffcbw.html

[T08] Kotlin：数据类
来源：http://dali.nanxinkj.top/Article/details/gtqlewystq.html

data class User(val name: String, val age: Int)
来源：http://dali.yueranfly.top/Article/details/gtisuybybe.html

[T09] Kotlin：扩展函数
来源：http://dali.zhixingplan.top/Article/details/gtjgqpktto.html

fun String.exclaim() = this + "!"
来源：http://dali.bjfxy.top/Article/details/gtdkmrrvbf.html

[T10] Kotlin：默认参数
来源：http://dali.hysaishi.cn/Article/details/gtywuqezrb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gogol.net.cn/Article/details/gtbdwzvjsc.html

[T11] Kotlin：协程
来源：http://dali.shuidangran.top/Article/details/gtdoyklvng.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.dashuyun.cn/Article/details/gtdprcfkgo.html

[T12] Kotlin：解构声明
来源：http://dali.guannengcc.top/Article/details/gtcafdpvai.html

val (a, b) = Pair(1, 2)
来源：http://dali.sysykeji.top/Article/details/gtgxydpolh.html

[T13] Kotlin：只读 Map
来源：http://dali.chenlongwang.top/Article/details/gtloyahkst.html

val m = mapOf("a" to 1)
来源：http://dali.jqgfzy.top/Article/details/gtljomkjew.html

[T14] Kotlin：循环
来源：http://dali.c1oappe.top/Article/details/gtfxbhvbid.html

for (i in 1..10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gtwjspwodq.html

[T15] Kotlin：接口
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivydwimr.html

interface Shape { fun area(): Double }
来源：http://dali.cqqwz.cn/Article/details/gtcqzcbiuh.html

[T16] Swift：Hello World
来源：http://dali.fengsongda.top/Article/details/gtftachayg.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gtcsogrygl.html

[T17] Swift：变量与常量
来源：http://dali.tianlin.xyz/Article/details/gtdaweyzda.html

var a = 1;  let b = 2
来源：http://dali.jiagoushi.top/Article/details/gtcgtrgqrv.html

[T18] Swift：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gtwhatuojk.html

"值: \(b)"
来源：http://dali.cashguo.top/Article/details/gtuvcrdhoc.html

[T19] Swift：可选绑定
来源：http://dali.xuetiantiany.cn/Article/details/gtsgirogtt.html

if let n = opt { print(n) }
来源：http://dali.pengpengdd.cyou/Article/details/gtsiihakuz.html

[T20] Swift：数组操作
来源：http://dali.chenjidiqi.icu/Article/details/gtcwohbkcu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cheryme.top/Article/details/gtzdbieysy.html

[T21] Swift：遍历
来源：http://dali.316326.xyz/Article/details/gtuxyxperg.html

for x in a { print(x) }
来源：http://dali.sweek.top/Article/details/gtawjvjdfc.html

[T22] Swift：字典
来源：http://dali.gotoacloud.top/Article/details/gthajxijii.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yangfankeji.com/Article/details/gtraznmujc.html

[T23] Swift：函数
来源：http://dali.fzhhl.top/Article/details/gtgcfynqoq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlssiexac.html

[T24] Swift：闭包
来源：http://dali.hammf.cn/Article/details/gtjzaxxyug.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlkssawq.html


<!-- 参考信息 -->