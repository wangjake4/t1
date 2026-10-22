代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenjidiqi.icu/Article/details/gtfcwzjbxj.html

[R24] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gtmlebizqi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.vqdsnc.cn/Article/details/gtsgummvxj.html

[R25] 去后缀 / 去前缀
来源：http://dali.jianghu66.top/Article/details/gtflhrldss.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.snrcjt.cn/Article/details/gtwcdqvoxx.html

[R26] 命令替换
来源：http://dali.kuanghao11.cn/Article/details/gtepbwjurq.html

now=$(date +%F); echo "$now"
来源：http://dali.gaohongyu789.top/Article/details/gttogpmdhd.html

[R27] 算术展开
来源：http://dali.yj20258888.top/Article/details/gtfpcrxmha.html

echo $((1 + 2 * 3))
来源：http://dali.quarkkingdee.top/Article/details/gtqqrmxrrc.html

[R28] 浮点运算
来源：http://dali.jiagoushi.top/Article/details/gtzrvswrdh.html

echo "scale=2; 10/3" | bc
来源：http://dali.jianghu66.top/Article/details/gtkmnrougb.html

[R29] 定义函数
来源：http://dali.daria6918.cn/Article/details/gtgcpnyemo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yangfankeji.com/Article/details/gtvagyymta.html

[R30] 函数返回状态码
来源：http://dali.zdqjudy.top/Article/details/gtxzdtedee.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.haohaochexian.top/Article/details/gttrtozdge.html

[R31] 局部变量
来源：http://dali.haohaochexian.top/Article/details/gtqxxzbubh.html

f() { local x=1; echo "$x"; }
来源：http://dali.nwbrower.top/Article/details/gtnxzfyfjo.html

[R32] 参数个数校验
来源：http://dali.hywenlv.cn/Article/details/gtpciyxmzx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gtucbnulhk.html

[R33] 捕获错误并提示行号
来源：http://dali.quarkkingdee.top/Article/details/gtnetgyrbp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jyoumei.cn/Article/details/gtchsctwzc.html

[R34] 退出时清理
来源：http://dali.iojbl.cn/Article/details/gtgzfzgpek.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gtfegzysrd.html

[R35] 后台执行并等待
来源：http://dali.fzhhl.top/Article/details/gthafxwuwn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dianchejie.cn/Article/details/gtwlxmfnnp.html

[R36] 并发执行多个任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysdibmkt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ppjwa.cn/Article/details/gtttrshcds.html

[R37] 把输出赋给变量
来源：http://dali.jyoumei.cn/Article/details/gtmjgvnqiz.html

files=$(ls -1)
来源：http://dali.0kj1m.cn/Article/details/gtxirrtnri.html

[R38] 管道串联
来源：http://dali.nanxinkj.top/Article/details/gtllokzxpu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shangyingyoupin.top/Article/details/gtzjrzejzw.html

[R39] 重定向标准输出与错误
来源：http://dali.xuetiantiany.cn/Article/details/gtsylmtclf.html

cmd > out.log 2>&1
来源：http://dali.ydzc1.top/Article/details/gtlrkuvldv.html

[R40] 追加写日志
来源：http://dali.shangyingyoupin.top/Article/details/gtmpyxlvlx.html

echo "log" >> out.log
来源：http://dali.fzhhl.top/Article/details/gtsylhprtx.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtsiimevlf.html

cmd >/dev/null 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gtrxscqhai.html

[R42] 输入重定向
来源：http://dali.316326.xyz/Article/details/gtzfdlnnaj.html

wc -l < a.txt
来源：http://dali.cashguo.top/Article/details/gtrvhbquvv.html

[R43] 按名字查找文件
来源：http://dali.gzhubu.top/Article/details/gtrznolwwi.html

find . -name "*.log" -type f
来源：http://dali.yanxiufei.cn/Article/details/gtauexavkq.html

[R44] 按修改时间查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynulobdx.html

find . -mtime -7 -type f
来源：http://dali.zhengqikj.top/Article/details/gtmuohiquq.html

[R45] 批量删除
来源：http://dali.birdmap.top/Article/details/gtruzjhdsu.html

find . -name "*.tmp" -delete
来源：http://dali.hywenlv.cn/Article/details/gtjagicyzq.html

[R46] 递归替换文件内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiqqjbdcg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenlongwang.top/Article/details/gtomxnehyt.html

[R47] sed 单行替换
来源：http://dali.9152youxi.cn/Article/details/gtmnzqatmd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtsvgsqraf.html

[R48] awk 取指定列
来源：http://dali.chenzaomai.com/Article/details/gtorvqsgeb.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtpmbbnpak.html

[R49] awk 带条件
来源：http://dali.tianlin.xyz/Article/details/gtufpmcbsm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258.top/Article/details/gtfktcrfum.html

[R50] awk 求和
来源：http://dali.jlsjyb.cn/Article/details/gtzhybmjum.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.haohaochexian.top/Article/details/gtssdvxehr.html

[R51] 排序去重取前几
来源：http://dali.shuidangran.top/Article/details/gtilgwhyjp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxinkj.top/Article/details/gtgfuutyvy.html

[R52] 统计行数
来源：http://dali.vqdsnc.cn/Article/details/gteopuzzfv.html

wc -l a.txt
来源：http://dali.guowangkeji.top/Article/details/gtkehmzvtm.html

[R53] 查看文件头与实时尾
来源：http://dali.zycfv.cn/Article/details/gtcmbjpkhs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.0kj1m.cn/Article/details/gtzekdllix.html

[R54] 比较两个文件
来源：http://dali.sufxvd.cn/Article/details/gtmutspfsb.html

diff a.txt b.txt
来源：http://dali.quarkkingdee.top/Article/details/gthknxnlbl.html

[R55] 压缩与解压
来源：http://dali.gzhubu.top/Article/details/gtxpuwdswe.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cqqwz.cn/Article/details/gtcuhcqicr.html

[R56] 远程拷贝
来源：http://dali.gotoacloud.top/Article/details/gtqchmrqdc.html

scp file user@host:/path/
来源：http://dali.zhoulong.xyz/Article/details/gtpqyolzrj.html

[R57] 远程执行命令
来源：http://dali.c1oappe.top/Article/details/gtfihltvws.html

ssh user@host 'uptime'
来源：http://dali.shzxlz.cn/Article/details/gtvdixufcj.html

[R58] 下载文件
来源：http://dali.yonumen.top/Article/details/gtevoirayv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.9152youxi.cn/Article/details/gttqtuxslv.html

[R59] 发 POST JSON
来源：http://dali.chenlongwang.top/Article/details/gtrygvgoac.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hongshengwenyu.top/Article/details/gtrlukigfv.html

[R60] 只看 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gtcyiuwbbt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hammf.cn/Article/details/gtjztsscge.html

[R61] 磁盘占用
来源：http://dali.xuanzx.com/Article/details/gtuwqdfqnj.html

df -h;  du -sh *
来源：http://dali.9152youxi.cn/Article/details/gtwyalxelj.html

[R62] 找最占空间的文件
来源：http://dali.0kj1m.cn/Article/details/gtskpievfb.html

du -ah . | sort -rh | head -10
来源：http://dali.andypj.xyz/Article/details/gtcvdaoiql.html

[R63] 内存与进程
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtpbjwhp.html

free -h;  ps aux | grep nginx
来源：http://dali.meibo888.top/Article/details/gthzdfqzbf.html

[R64] 结束进程
来源：http://dali.sweek.top/Article/details/gtsqokvubf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhiwuduotai.top/Article/details/gtxukwtnzt.html

[R65] 查看端口占用
来源：http://dali.cdnleiting.top/Article/details/gtxvkkyrwf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cdnleiting.top/Article/details/gtyrjaqdfa.html

[R66] 定时任务
来源：http://dali.snrcjt.cn/Article/details/gtidubtufp.html

crontab -e;  crontab -l
来源：http://dali.havefunace.top/Article/details/gtwpqaibcg.html

[R67] 生成随机十六进制串
来源：http://dali.nanxinkj.top/Article/details/gterdtybma.html

openssl rand -hex 16
来源：http://dali.mhx1999.top/Article/details/gtkqucperk.html

[R68] 计算文件校验值
来源：http://dali.sweek.top/Article/details/gtnosolubg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvvumjmf.html

[R69] 生成随机密码
来源：http://dali.zhoulong.xyz/Article/details/gtazwukrmz.html

head -c 16 /dev/urandom | base64
来源：http://dali.xziqi.cn/Article/details/gtpnkmsxra.html

[R70] 时间戳与互转
来源：http://dali.hfpthk.cn/Article/details/gtpaazuebd.html

date +%s;  date -d @1700000000
来源：http://dali.ydzc1.top/Article/details/gtdaluecbz.html

[R71] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gtkorkntzx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.iojbl.cn/Article/details/gtayqhnazj.html

[R72] 等待端口就绪
来源：http://dali.yonumen.top/Article/details/gtlstdgrbc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gtifyblqfm.html

[R73] 分割大日志
来源：http://dali.sweek.top/Article/details/gtjumdvymm.html

split -l 1000 big.log part_
来源：http://dali.nwbrower.top/Article/details/gtysjelgso.html

[R74] 批量重命名
来源：http://dali.sysykeji.top/Article/details/gtbzytgusy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.vqdsnc.cn/Article/details/gtcwjzyooh.html

[R75] 导出环境变量
来源：http://dali.haohaochexian.top/Article/details/gtlcjgnwxe.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gogol.net.cn/Article/details/gtjxuauptt.html

[R76] 使用临时文件
来源：http://dali.tian-w.cn/Article/details/gtbnjzvtci.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gtjdwmhlko.html

[R77] 读取用户输入
来源：http://dali.ppjwa.cn/Article/details/gtibwhihjv.html

read -rp "请输入: " ans
来源：http://dali.havefunace.top/Article/details/gtuyubrbdg.html

[R78] 交互式菜单
来源：http://dali.yj20258.top/Article/details/gtpneagohi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fzhhl.top/Article/details/gtvtbbwijr.html

[R79] 解析命令行选项
来源：http://dali.tanke756.top/Article/details/gttdtavovy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.redwolf501.top/Article/details/gtunxnltad.html

[R80] 查看脚本执行耗时
来源：http://dali.tianlin.xyz/Article/details/gtiahcstss.html

time ./run.sh
来源：http://dali.andypj.xyz/Article/details/gtaatljbtg.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtakydwany.html

S. C / C++ 专题
来源：http://dali.yuxming.cn/Article/details/gthachqvjj.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtqcdauiwg.html

[S01] C：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdoerjtz.html

#include <stdio.h>
来源：http://dali.chenlongwang.top/Article/details/gtuadesacp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.pycfn.com/Article/details/gtbxbigtkl.html

[S02] C：变量与格式化输出
来源：http://dali.zycfv.cn/Article/details/gtwxnsilml.html

int a = 10; printf("%d\n", a);
来源：http://dali.nwbrower.top/Article/details/gteexqzifa.html

[S03] C：读入整数
来源：http://dali.kuanghao11.cn/Article/details/gtdbpkfios.html

int x; scanf("%d", &x);
来源：http://dali.ivvv.top/Article/details/gtkimwmbbo.html

[S04] C：字符串复制
来源：http://dali.yj20258.top/Article/details/gtpygpxqhr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cdnleiting.top/Article/details/gtbgceypof.html

[S05] C：字符串长度
来源：http://dali.daxiang520.top/Article/details/gtbrrgvnes.html

strlen(s)
来源：http://dali.yuanzhike.top/Article/details/gtzajucpxk.html

[S06] C：字符串比较
来源：http://dali.hnqzz.top/Article/details/gttadtbhba.html

strcmp(a, b) == 0
来源：http://dali.gzhubu.top/Article/details/gtgjvspdjr.html

[S07] C：数组遍历求和
来源：http://dali.feifeiyinyue.top/Article/details/gtijewmfdl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dashuyun.cn/Article/details/gtjjvflgrj.html

[S08] C：动态内存分配与释放
来源：http://dali.xuetiantiany.cn/Article/details/gtjeqazbad.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.svipenyu.cn/Article/details/gtumuqsanv.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxlrmgsd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xinyue.icu/Article/details/gtavmulpro.html

[S10] C：指针与解引用
来源：http://dali.jinghuilouyu.cn/Article/details/gtuaadhzeb.html

int *p = &a;  *p = 5;
来源：http://dali.chenlongwang.top/Article/details/gthuslzves.html

[S11] C：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gtjtqrchlg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.andypj.xyz/Article/details/gtuauldmpe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ydzc1.top/Article/details/gttnzigids.html

fclose(f);
来源：http://dali.tian-w.cn/Article/details/gtqracyqqs.html

[S12] C：写文件
来源：http://dali.dashuyun.cn/Article/details/gtoupykewl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gtnqetbvwu.html

[S13] C：宏定义
来源：http://dali.gogol.net.cn/Article/details/gtpoqoiqzw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.9152youxi.cn/Article/details/gtbzzgrxdw.html

[S14] C：枚举
来源：http://dali.ydzc1.top/Article/details/gtuvvthvjq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.iojbl.cn/Article/details/gtpfgzyzel.html

[S15] C：类型转换
来源：http://dali.gotoacloud.top/Article/details/gtyjqwuace.html

(double) a / b
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwdmxwfm.html

[S16] C：位操作置位
来源：http://dali.sufxvd.cn/Article/details/gtgplysgzc.html

x |= (1 << 3);
来源：http://dali.tian-w.cn/Article/details/gtolgyeill.html

[S17] C：安全拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtgrlbbwkt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gtoevzbwbe.html

[S18] C：命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gthvpbcrge.html

int main(int argc, char **argv)
来源：http://dali.yonumen.top/Article/details/gtvcxguvkt.html

[S19] C：快速排序
来源：http://dali.jinqigufen.top/Article/details/gttivliqym.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.snrcjt.cn/Article/details/gtvizurspo.html

[S20] C：二分查找
来源：http://dali.jinqigfzy.top/Article/details/gtulkerhqn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gtgjhuqsti.html

[S21] C：字符类别判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkuhldchy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.quarkkingdee.top/Article/details/gterzhbjuh.html

[S22] C：字符串转数字
来源：http://dali.zhengqikj.top/Article/details/gtfvjslkua.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhongyouzk.top/Article/details/gtogpdbdpv.html

[S23] C：随机数
来源：http://dali.aibaodan.cn/Article/details/gtawufuqwj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hongshengwenyu.top/Article/details/gtpqehaxvn.html

[S24] C：获取本地时间
来源：http://dali.dashuyun.cn/Article/details/gttsyyejgg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sysykeji.top/Article/details/gtxxjkaqwu.html

[S25] C：内存拷贝
来源：http://dali.yueranfly.top/Article/details/gthgmhzekw.html

memcpy(dst, src, n);
来源：http://dali.chenjidiqi.icu/Article/details/gtklpwulzc.html

[S26] C：内存清零
来源：http://dali.gogol.net.cn/Article/details/gtxtwhptwf.html

memset(a, 0, sizeof a);
来源：http://dali.zhixingplan.top/Article/details/gtalavdugd.html

[S27] C：定义常量
来源：http://dali.svipenyu.cn/Article/details/gtbnlxudku.html

const double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtcijssooz.html

[S28] C：静态变量
来源：http://dali.zdqjudy.top/Article/details/gtylqkrxuk.html

static int counter = 0;
来源：http://dali.smart0.xyz/Article/details/gtqnqlhmza.html

[S29] C：变参函数
来源：http://dali.zycfv.cn/Article/details/gtkxfgiagi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.svipenyu.cn/Article/details/gtwcpeiuqc.html

[S30] C：头文件保护
来源：http://dali.jinqigfzy.top/Article/details/gtuulakipc.html

#ifndef X_H
来源：http://dali.quarkkingdee.top/Article/details/gtlkrsqjjl.html

#define X_H
来源：http://dali.cucudq.cn/Article/details/gtcswzymox.html

#endif
来源：http://dali.kuanghao11.cn/Article/details/gtruiqevkq.html

[S31] C++：Hello World
来源：http://dali.yvedp.cn/Article/details/gtyozmxgtj.html

#include <iostream>
来源：http://dali.jianghu66.top/Article/details/gttmlasvlh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jyoumei.cn/Article/details/gtulykoeva.html

[S32] C++：字符串
来源：http://dali.yueranfly.top/Article/details/gtmxfgkceh.html

std::string s = "hi";  s += "!";
来源：http://dali.quarkkingdee.top/Article/details/gtflutaffn.html

[S33] C++：vector 增删
来源：http://dali.chenjidiqi.icu/Article/details/gttbnlcdyk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yongpay.top/Article/details/gtufcijwqv.html

[S34] C++：遍历 vector
来源：http://dali.kuanghao11.cn/Article/details/gtirmhwzmz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cucudq.cn/Article/details/gtdowweufi.html

[S35] C++：map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbglmxqut.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtbbgthuai.html

[S36] C++：unordered_map
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdnawaafb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtwcbaofdj.html

[S37] C++：set
来源：http://dali.yvedp.cn/Article/details/gtrfnexfpg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zycfv.cn/Article/details/gttfrqjxaw.html

[S38] C++：排序
来源：http://dali.gzhubu.top/Article/details/gthbfznazu.html

std::sort(v.begin(), v.end());
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzjnawim.html

[S39] C++：自定义比较器排序
来源：http://dali.xylfe.cn/Article/details/gtxbytttlj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hongshengwenyu.top/Article/details/gtvhstidjm.html

[S40] C++：查找元素
来源：http://dali.nwbrower.top/Article/details/gtrbgkqohl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.meibo888.top/Article/details/gtoffbjbuq.html

[S41] C++：类与构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqcqwdvg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.quarkkingdee.top/Article/details/gtvptfbcom.html

[S42] C++：继承与虚函数
来源：http://dali.ybcxt.top/Article/details/gtkqfavlhf.html

class B : public Base { public: void f() override {} };
来源：http://dali.meibo888.top/Article/details/gtvlvomvoj.html

[S43] C++：智能指针
来源：http://dali.ydzc1.top/Article/details/gtjvpirpwg.html

auto p = std::make_unique<int>(5);
来源：http://dali.c1oappe.top/Article/details/gtzziokmmb.html

[S44] C++：引用传参
来源：http://dali.zhengqikj.top/Article/details/gtmsdeyjap.html

void inc(int &x) { ++x; }
来源：http://dali.yonumen.top/Article/details/gtaxcqmsch.html

[S45] C++：lambda
来源：http://dali.ehwqpu.com/Article/details/gtrmhsxdgp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.andypj.xyz/Article/details/gtxycsdolk.html

[S46] C++：函数模板
来源：http://dali.0kj1m.cn/Article/details/gttyaxpwil.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.aibaodan.cn/Article/details/gtixvdwydi.html

[S47] C++：结构化绑定遍历
来源：http://dali.redwolf501.top/Article/details/gtikcykkcb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.birdmap.top/Article/details/gtpuciyqpz.html

[S48] C++：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtdlaoimwb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigfzy.top/Article/details/gtlsdjtgqe.html

while (std::getline(in, line)) { }
来源：http://dali.ybcxt.top/Article/details/gtunmqhbns.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gtwsumbwwz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ehwqpu.com/Article/details/gtnzoxesjh.html

[S50] C++：格式化数字
来源：http://dali.chenzaomai.com/Article/details/gtabbvsitk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtknvgpqtw.html

[S51] C++：显式类型转换
来源：http://dali.chenlongwang.top/Article/details/gtpdwwvbnp.html

static_cast<double>(a) / b
来源：http://dali.nwbrower.top/Article/details/gtzotkkykc.html

[S52] C++：const 与 noexcept
来源：http://dali.meibo888.top/Article/details/gtaixuwlbp.html

int size() const noexcept { return n_; }
来源：http://dali.hysaishi.cn/Article/details/gtbvzsuvrk.html

[S53] C++：移动语义
来源：http://dali.hnqzz.top/Article/details/gtdikvfowh.html

std::vector<int> w = std::move(v);
来源：http://dali.fengsongda.top/Article/details/gtpdaeyedr.html

[S54] C++：异常处理
来源：http://dali.hysaishi.cn/Article/details/gtxjzbgrzh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.redwolf501.top/Article/details/gtejjffmrh.html

[S55] C++：结构化绑定
来源：http://dali.redwolf501.top/Article/details/gtflwpvnxd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.smart0.xyz/Article/details/gtanhdycev.html

[S56] C++：optional
来源：http://dali.daria6918.cn/Article/details/gtuxrqrsdq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnqzz.top/Article/details/gtcxagluhb.html

[S57] C++：编译期常量
来源：http://dali.jinqigfzy.top/Article/details/gtqnssklag.html

constexpr int N = 10;
来源：http://dali.zhoulong.xyz/Article/details/gtqmsglaiy.html

[S58] C++：命名空间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqlunnaj.html

namespace ns { int f() { return 1; } }
来源：http://dali.guowangkeji.top/Article/details/gtqordiuoy.html

[S59] C++：静态断言
来源：http://dali.9152youxi.cn/Article/details/gtemwpyizw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenzaomai.com/Article/details/gtkfezkevk.html

[S60] C++：遍历并删除元素
来源：http://dali.zhiwuduotai.top/Article/details/gtlvfqiwwy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gthhkmkjqu.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gthvgdtjgn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangtech.top/Article/details/gtgneacfxg.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtzphxbccw.html

[T01] Kotlin：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtecmjaooh.html

println("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtyqykfdsv.html

[T02] Kotlin：变量
来源：http://dali.xylfe.cn/Article/details/gtbswzudfz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hysaishi.cn/Article/details/gtzfhwprap.html

[T03] Kotlin：字符串模板
来源：http://dali.cdnleiting.top/Article/details/gtvzjmtvnc.html

"值: $b"
来源：http://dali.jyoumei.cn/Article/details/gtswpvvlzg.html

[T04] Kotlin：空安全
来源：http://dali.pycfn.com/Article/details/gthiybcxif.html

val n: String? = null;  n?.length
来源：http://dali.gaohongyu789.top/Article/details/gtqtcvjfxf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gtcwaifpva.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuanzhike.top/Article/details/gtlpbqsdjr.html

[T06] Kotlin：集合映射
来源：http://dali.guowangkeji.top/Article/details/gtxazdvmke.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sufxvd.cn/Article/details/gtygmaiioa.html

[T07] Kotlin：集合过滤
来源：http://dali.shuidangran.top/Article/details/gtdecqjcom.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jlsjyb.cn/Article/details/gtsamcisne.html

[T08] Kotlin：数据类
来源：http://dali.shzxlz.cn/Article/details/gtczjkznmj.html

data class User(val name: String, val age: Int)
来源：http://dali.havefunace.top/Article/details/gtgaknjvmm.html

[T09] Kotlin：扩展函数
来源：http://dali.dashuyun.cn/Article/details/gtmortktwu.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsvflefq.html

[T10] Kotlin：默认参数
来源：http://dali.zhiwuduotai.top/Article/details/gttjdtbjph.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jiagoushi.top/Article/details/gtbadbbahv.html

[T11] Kotlin：协程
来源：http://dali.chenlongwang.top/Article/details/gtzgdryvur.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gogol.net.cn/Article/details/gtfwrfafld.html

[T12] Kotlin：解构声明
来源：http://dali.sxryk.cn/Article/details/gtylzjfvyi.html

val (a, b) = Pair(1, 2)
来源：http://dali.316326.xyz/Article/details/gtnnzbsqic.html

[T13] Kotlin：只读 Map
来源：http://dali.hnxiangtu.top/Article/details/gtviirmgqu.html

val m = mapOf("a" to 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmohayjs.html

[T14] Kotlin：循环
来源：http://dali.ivvv.top/Article/details/gtegutnssw.html

for (i in 1..10) println(i)
来源：http://dali.yj20258888.top/Article/details/gtdolvfjuf.html

[T15] Kotlin：接口
来源：http://dali.gaohongyu789.top/Article/details/gtjaffvofo.html

interface Shape { fun area(): Double }
来源：http://dali.quarkkingdee.top/Article/details/gtavrfxlxl.html

[T16] Swift：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtfpdkhlvt.html

print("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbawcclf.html

[T17] Swift：变量与常量
来源：http://dali.haohaochexian.top/Article/details/gtutvipntj.html

var a = 1;  let b = 2
来源：http://dali.ppjwa.cn/Article/details/gtkukylnbi.html

[T18] Swift：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtmsbzcqmf.html

"值: \(b)"
来源：http://dali.0kj1m.cn/Article/details/gtkfgtshdo.html

[T19] Swift：可选绑定
来源：http://dali.hnqzz.top/Article/details/gtnvopphpy.html

if let n = opt { print(n) }
来源：http://dali.hywenlv.cn/Article/details/gtusmquliw.html

[T20] Swift：数组操作
来源：http://dali.guannengcc.top/Article/details/gtuzrbjqro.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yueranfly.top/Article/details/gtoeopjneg.html

[T21] Swift：遍历
来源：http://dali.xuanzx.com/Article/details/gtsoubanxh.html

for x in a { print(x) }
来源：http://dali.cheryme.top/Article/details/gtdtkezcpv.html

[T22] Swift：字典
来源：http://dali.birdmap.top/Article/details/gtriekdbfb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gaohongyu789.top/Article/details/gtlwgialgr.html

[T23] Swift：函数
来源：http://dali.jyoumei.cn/Article/details/gtnqfupwat.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtaeluqbiv.html

[T24] Swift：闭包
来源：http://dali.jinqigufen.top/Article/details/gtyezlyvxr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sxryk.cn/Article/details/gtraljygrg.html

[T25] Swift：结构体
来源：http://dali.xuanzx.com/Article/details/gtlohuwhod.html

struct P { var x: Int }
来源：http://dali.jlsjyb.cn/Article/details/gtamfgxkea.html

[T26] Swift：类与重写
来源：http://dali.yueranfly.top/Article/details/gtchrxmhce.html

class A: Base { override func f() {} }
来源：http://dali.0kj1m.cn/Article/details/gthstyfxmm.html


<!-- 参考信息 -->