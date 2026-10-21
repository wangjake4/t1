代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenzaomai.com/Article/details/gtrejdwimj.html

[R16] until 等待条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxxtmsee.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gtxicrmwmj.html

[R17] 数组定义与取值
来源：http://dali.cdnleiting.top/Article/details/gtjwyyjshn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cucudq.cn/Article/details/gtnqyihvic.html

[R18] 遍历数组
来源：http://dali.cqqwz.cn/Article/details/gtclhbvnvf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.havefunace.top/Article/details/gtjypcwkks.html

[R19] 数组长度
来源：http://dali.hywenlv.cn/Article/details/gtmkexiyqd.html

echo "${#arr[@]}"
来源：http://dali.dashuyun.cn/Article/details/gtwcettxih.html

[R20] 关联数组（字典）
来源：http://dali.ydzc1.top/Article/details/gtpcusgzjf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqlkcnrv.html

[R21] 字符串长度
来源：http://dali.xziqi.cn/Article/details/gtvelpwzov.html

echo "${#s}"
来源：http://dali.yueranfly.top/Article/details/gthvlpkupu.html

[R22] 截取子串
来源：http://dali.jyoumei.cn/Article/details/gtqndkreaq.html

echo "${s:0:5}"
来源：http://dali.xinyue.icu/Article/details/gtluqfponv.html

[R23] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gtmteorqck.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xylfe.cn/Article/details/gtobtptbjg.html

[R24] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gthmjguqwa.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhihtsox.html

[R25] 去后缀 / 去前缀
来源：http://dali.mhx1999.top/Article/details/gtpgqbaffj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgtgbtfc.html

[R26] 命令替换
来源：http://dali.cqqwz.cn/Article/details/gtvxdgrveu.html

now=$(date +%F); echo "$now"
来源：http://dali.316326.xyz/Article/details/gtycqadclu.html

[R27] 算术展开
来源：http://dali.wangshuangyany.cn/Article/details/gtxokhhnth.html

echo $((1 + 2 * 3))
来源：http://dali.0kj1m.cn/Article/details/gtajymqsxr.html

[R28] 浮点运算
来源：http://dali.vqdsnc.cn/Article/details/gtwidxxqkr.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenzaomai.com/Article/details/gteaptwqan.html

[R29] 定义函数
来源：http://dali.gogol.net.cn/Article/details/gtbxumhpjg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnqzz.top/Article/details/gtmbprgerj.html

[R30] 函数返回状态码
来源：http://dali.mhx1999.top/Article/details/gtyxuwrhyk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shuidangran.top/Article/details/gtzoyjmkrd.html

[R31] 局部变量
来源：http://dali.gaohongyu789.top/Article/details/gtlmhdquiq.html

f() { local x=1; echo "$x"; }
来源：http://dali.aizwys.cn/Article/details/gtwpsfiauc.html

[R32] 参数个数校验
来源：http://dali.zhongyouzk.top/Article/details/gtfhmirada.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gtrblvclem.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigufen.top/Article/details/gtpjjoruoq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guowangkeji.top/Article/details/gtfmnmaieg.html

[R34] 退出时清理
来源：http://dali.sxryk.cn/Article/details/gtpxpmpdzz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.mhx1999.top/Article/details/gtmeaswrdf.html

[R35] 后台执行并等待
来源：http://dali.shzxlz.cn/Article/details/gtghhnuuna.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ehwqpu.com/Article/details/gtrzvovvhn.html

[R36] 并发执行多个任务
来源：http://dali.shangyingyoupin.top/Article/details/gthslwvynq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hysaishi.cn/Article/details/gtjrqonpvz.html

[R37] 把输出赋给变量
来源：http://dali.daria6918.cn/Article/details/gttxuallcl.html

files=$(ls -1)
来源：http://dali.yangfankeji.com/Article/details/gttymlfjsp.html

[R38] 管道串联
来源：http://dali.jqgufenzy.top/Article/details/gtuqgcgqmo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sufxvd.cn/Article/details/gtzigcsjmu.html

[R39] 重定向标准输出与错误
来源：http://dali.ppjwa.cn/Article/details/gtdqzycbuj.html

cmd > out.log 2>&1
来源：http://dali.ydzc1.top/Article/details/gtdadrsmfd.html

[R40] 追加写日志
来源：http://dali.0kj1m.cn/Article/details/gtdlgeerdi.html

echo "log" >> out.log
来源：http://dali.yj202588.top/Article/details/gtnwwjwdcc.html

[R41] 丢弃输出
来源：http://dali.yuanzhike.top/Article/details/gtmluflyom.html

cmd >/dev/null 2>&1
来源：http://dali.jqgfzy.top/Article/details/gtwdlcimto.html

[R42] 输入重定向
来源：http://dali.cqqwz.cn/Article/details/gthwatlswg.html

wc -l < a.txt
来源：http://dali.jyoumei.cn/Article/details/gthamnvzah.html

[R43] 按名字查找文件
来源：http://dali.gaohongyu789.top/Article/details/gtvotzqejm.html

find . -name "*.log" -type f
来源：http://dali.ehwqpu.com/Article/details/gtswenadrm.html

[R44] 按修改时间查找
来源：http://dali.yj202588.top/Article/details/gtthiwueag.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gtzzewshbl.html

[R45] 批量删除
来源：http://dali.zhiwuduotai.top/Article/details/gtowpvqqeu.html

find . -name "*.tmp" -delete
来源：http://dali.mhx1999.top/Article/details/gtgrqazdwj.html

[R46] 递归替换文件内容
来源：http://dali.ydzc1.top/Article/details/gtshdrfkbm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.snrcjt.cn/Article/details/gtnzgcwcqc.html

[R47] sed 单行替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyganlgen.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuxming.cn/Article/details/gtpxkecxsj.html

[R48] awk 取指定列
来源：http://dali.c1oappe.top/Article/details/gtbxeghzvy.html

awk '{print $1, $3}' a.txt
来源：http://dali.fzhhl.top/Article/details/gtuojplzkw.html

[R49] awk 带条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtcbglky.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yanxiufei.cn/Article/details/gteuwnrenn.html

[R50] awk 求和
来源：http://dali.cheryme.top/Article/details/gtifteaobn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj20258.top/Article/details/gtwvtgqdof.html

[R51] 排序去重取前几
来源：http://dali.ehwqpu.com/Article/details/gtcbkvlrwg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyrxayic.html

[R52] 统计行数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxdrvpfn.html

wc -l a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtkzqgmtbk.html

[R53] 查看文件头与实时尾
来源：http://dali.xuanzx.com/Article/details/gtidziuwwq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhixingplan.top/Article/details/gtcutvwids.html

[R54] 比较两个文件
来源：http://dali.dianchejie.cn/Article/details/gtsblxsqrk.html

diff a.txt b.txt
来源：http://dali.meibo888.top/Article/details/gtcyttjwdw.html

[R55] 压缩与解压
来源：http://dali.pycfn.com/Article/details/gtijravjwy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sweek.top/Article/details/gtovfudswd.html

[R56] 远程拷贝
来源：http://dali.meibo888.top/Article/details/gteooyqocl.html

scp file user@host:/path/
来源：http://dali.hywenlv.cn/Article/details/gtmdjwtkkm.html

[R57] 远程执行命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gtveygnkos.html

ssh user@host 'uptime'
来源：http://dali.316326.xyz/Article/details/gtkcfsdrrh.html

[R58] 下载文件
来源：http://dali.hongshengwenyu.top/Article/details/gtvedxkbkg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pycfn.com/Article/details/gtkbobcgqx.html

[R59] 发 POST JSON
来源：http://dali.redwolf501.top/Article/details/gttfmmudzt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yongpay.top/Article/details/gtwmfknulo.html

[R60] 只看 HTTP 状态码
来源：http://dali.ybcxt.top/Article/details/gtdspudkyc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nwbrower.top/Article/details/gtyamnwkry.html

[R61] 磁盘占用
来源：http://dali.zycfv.cn/Article/details/gtwvufmthb.html

df -h;  du -sh *
来源：http://dali.smart0.xyz/Article/details/gtswjgbtks.html

[R62] 找最占空间的文件
来源：http://dali.0kj1m.cn/Article/details/gtjrcwwatp.html

du -ah . | sort -rh | head -10
来源：http://dali.gzhubu.top/Article/details/gtgjsuwcrb.html

[R63] 内存与进程
来源：http://dali.daxiang520.top/Article/details/gtmfzplbkl.html

free -h;  ps aux | grep nginx
来源：http://dali.xuanzx.com/Article/details/gtlmzfdocp.html

[R64] 结束进程
来源：http://dali.daxiang520.top/Article/details/gtwulglsqp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.havefunace.top/Article/details/gtelnapdkl.html

[R65] 查看端口占用
来源：http://dali.yj202588.top/Article/details/gtlptjvnrg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.snrcjt.cn/Article/details/gtyasbxdmg.html

[R66] 定时任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqkhtdcg.html

crontab -e;  crontab -l
来源：http://dali.sxryk.cn/Article/details/gtgtaxnwvp.html

[R67] 生成随机十六进制串
来源：http://dali.0kj1m.cn/Article/details/gtyomtksuw.html

openssl rand -hex 16
来源：http://dali.shangyingyoupin.top/Article/details/gtnipsvylc.html

[R68] 计算文件校验值
来源：http://dali.feifeiyinyue.top/Article/details/gtsyzlmnbx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtyglsnhvx.html

[R69] 生成随机密码
来源：http://dali.ivvv.top/Article/details/gteinejwuj.html

head -c 16 /dev/urandom | base64
来源：http://dali.birdmap.top/Article/details/gtecjqnevt.html

[R70] 时间戳与互转
来源：http://dali.tianlin.xyz/Article/details/gtsxpxolhg.html

date +%s;  date -d @1700000000
来源：http://dali.jiagoushi.top/Article/details/gttuuyxxrb.html

[R71] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtftpzymch.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ydzc1.top/Article/details/gtzeyeoolh.html

[R72] 等待端口就绪
来源：http://dali.ydzc1.top/Article/details/gtsowfraaf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gtqtwgxbfw.html

[R73] 分割大日志
来源：http://dali.jiagoushi.top/Article/details/gtnuaiufyi.html

split -l 1000 big.log part_
来源：http://dali.ivvv.top/Article/details/gtfvcbtxtz.html

[R74] 批量重命名
来源：http://dali.zhiwuduotai.top/Article/details/gtaeajemxy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cucudq.cn/Article/details/gtlajxzmuo.html

[R75] 导出环境变量
来源：http://dali.jlsjyb.cn/Article/details/gtgyucitfo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shzxlz.cn/Article/details/gtrsnsnxld.html

[R76] 使用临时文件
来源：http://dali.tanke756.top/Article/details/gtgmjwbwtw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gtlvryqsgs.html

[R77] 读取用户输入
来源：http://dali.sweek.top/Article/details/gtdphfdztx.html

read -rp "请输入: " ans
来源：http://dali.pengpengdd.cyou/Article/details/gtehgtdffp.html

[R78] 交互式菜单
来源：http://dali.fengsongda.top/Article/details/gtqhvggqvd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.smart0.xyz/Article/details/gtwahwapwk.html

[R79] 解析命令行选项
来源：http://dali.gzhubu.top/Article/details/gtpbiegsnv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.havefunace.top/Article/details/gtmswzfpiv.html

[R80] 查看脚本执行耗时
来源：http://dali.wangshuangyany.cn/Article/details/gtdcwxzkda.html

time ./run.sh
来源：http://dali.daria6918.cn/Article/details/gtniexvlmq.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtbxhsajos.html

S. C / C++ 专题
来源：http://dali.dianchejie.cn/Article/details/gtpcgosshn.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtaihaspzc.html

[S01] C：Hello World
来源：http://dali.tian-w.cn/Article/details/gtrqhfivcu.html

#include <stdio.h>
来源：http://dali.hongshengwenyu.top/Article/details/gtiorbvskr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkmiyacj.html

[S02] C：变量与格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gtijscfbrr.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxinkj.top/Article/details/gtdpjthsqr.html

[S03] C：读入整数
来源：http://dali.gogol.net.cn/Article/details/gtjfopbpnr.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gtejgcdbmt.html

[S04] C：字符串复制
来源：http://dali.smart0.xyz/Article/details/gtobocxoct.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.bjfxy.top/Article/details/gtgayhszqf.html

[S05] C：字符串长度
来源：http://dali.guowangkeji.top/Article/details/gtnissgnic.html

strlen(s)
来源：http://dali.yj20258.top/Article/details/gtashqdacg.html

[S06] C：字符串比较
来源：http://dali.hammf.cn/Article/details/gtqfrtzvve.html

strcmp(a, b) == 0
来源：http://dali.hnxiangtu.top/Article/details/gtduihruhj.html

[S07] C：数组遍历求和
来源：http://dali.fzhhl.top/Article/details/gtbshffvir.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cqqwz.cn/Article/details/gtkmlbrviy.html

[S08] C：动态内存分配与释放
来源：http://dali.sxryk.cn/Article/details/gtishzclgu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj202588.top/Article/details/gtaesseosj.html

[S09] C：结构体定义与初始化
来源：http://dali.hfpthk.cn/Article/details/gtfjuvtotl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258888.top/Article/details/gtfnvjshrg.html

[S10] C：指针与解引用
来源：http://dali.nwbrower.top/Article/details/gtysxdokcb.html

int *p = &a;  *p = 5;
来源：http://dali.ivvv.top/Article/details/gtgocurjqf.html

[S11] C：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtflligtrw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ehwqpu.com/Article/details/gtkdtylwbr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.svipenyu.cn/Article/details/gtgneitmhv.html

fclose(f);
来源：http://dali.andypj.xyz/Article/details/gtgzlyryii.html

[S12] C：写文件
来源：http://dali.jianghu66.top/Article/details/gtdmayseew.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gtemwfigvb.html

[S13] C：宏定义
来源：http://dali.hammf.cn/Article/details/gtwdhophej.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gaohongyu789.top/Article/details/gtqxclgqam.html

[S14] C：枚举
来源：http://dali.jlsjyb.cn/Article/details/gtwhooxloc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yvedp.cn/Article/details/gtgmrttgeb.html

[S15] C：类型转换
来源：http://dali.daxiang520.top/Article/details/gtlekadgpa.html

(double) a / b
来源：http://dali.guowangkeji.top/Article/details/gtgumbwheg.html

[S16] C：位操作置位
来源：http://dali.sweek.top/Article/details/gtsremysrr.html

x |= (1 << 3);
来源：http://dali.haohaochexian.top/Article/details/gtxvaqrrpx.html

[S17] C：安全拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtjidbcxmo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guannengcc.top/Article/details/gteqsvqapk.html

[S18] C：命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gtqhcvbkpg.html

int main(int argc, char **argv)
来源：http://dali.xziqi.cn/Article/details/gtkjrqvznd.html

[S19] C：快速排序
来源：http://dali.zhixingplan.top/Article/details/gtcnurqmkt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gteojuakmq.html

[S20] C：二分查找
来源：http://dali.hnqzz.top/Article/details/gtseiqhdtn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gtehveyvaa.html

[S21] C：字符类别判断
来源：http://dali.zhiwuduotai.top/Article/details/gtqhezdcaj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenzaomai.com/Article/details/gtvkgywlor.html

[S22] C：字符串转数字
来源：http://dali.jianghu66.top/Article/details/gtkabyjwfs.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jiagoushi.top/Article/details/gtymrfjnmd.html

[S23] C：随机数
来源：http://dali.gotoacloud.top/Article/details/gtjrgfelhy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.havefunace.top/Article/details/gtgbcyoxbb.html

[S24] C：获取本地时间
来源：http://dali.redwolf501.top/Article/details/gttnfrpfya.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guannengcc.top/Article/details/gtsdimsfnv.html

[S25] C：内存拷贝
来源：http://dali.zycfv.cn/Article/details/gtuxrorjaq.html

memcpy(dst, src, n);
来源：http://dali.tanke756.top/Article/details/gtschfrozx.html

[S26] C：内存清零
来源：http://dali.zhengqikj.top/Article/details/gtmfpiycto.html

memset(a, 0, sizeof a);
来源：http://dali.daxiang520.top/Article/details/gteogirhsd.html

[S27] C：定义常量
来源：http://dali.svipenyu.cn/Article/details/gtkbbghfzw.html

const double PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gttzgjpune.html

[S28] C：静态变量
来源：http://dali.havefunace.top/Article/details/gtikqvfttm.html

static int counter = 0;
来源：http://dali.yonumen.top/Article/details/gtiqijrbui.html

[S29] C：变参函数
来源：http://dali.jqgfzy.top/Article/details/gtrugpsggz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnxiangtu.top/Article/details/gtwtqgjefc.html

[S30] C：头文件保护
来源：http://dali.fengsongda.top/Article/details/gtcczgnqve.html

#ifndef X_H
来源：http://dali.dashuyun.cn/Article/details/gtbgndbgtr.html

#define X_H
来源：http://dali.mhx1999.top/Article/details/gtcdvtbbrk.html

#endif
来源：http://dali.zhixingplan.top/Article/details/gtozicrncj.html

[S31] C++：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtlzniyczg.html

#include <iostream>
来源：http://dali.c1oappe.top/Article/details/gtjdirwlwn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sysykeji.top/Article/details/gtfbdnqyqi.html

[S32] C++：字符串
来源：http://dali.guowangkeji.top/Article/details/gtmwnhkthq.html

std::string s = "hi";  s += "!";
来源：http://dali.ivvv.top/Article/details/gtijeqrwkk.html

[S33] C++：vector 增删
来源：http://dali.iojbl.cn/Article/details/gtshfhozss.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.snrcjt.cn/Article/details/gtaewgcooz.html

[S34] C++：遍历 vector
来源：http://dali.quarkkingdee.top/Article/details/gtlgzsiktk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jianghu66.top/Article/details/gtgdedhpxl.html

[S35] C++：map
来源：http://dali.hammf.cn/Article/details/gteydihsrh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gtowyclemf.html

[S36] C++：unordered_map
来源：http://dali.cdnleiting.top/Article/details/gtujgjpzij.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtlacgtsqv.html

[S37] C++：set
来源：http://dali.jlsjyb.cn/Article/details/gtkebejfnk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tanke756.top/Article/details/gtwlifipcy.html

[S38] C++：排序
来源：http://dali.cucudq.cn/Article/details/gttysopsjn.html

std::sort(v.begin(), v.end());
来源：http://dali.hysaishi.cn/Article/details/gtnshibfyf.html

[S39] C++：自定义比较器排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtajqtfnvy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tianlin.xyz/Article/details/gttytnqjmw.html

[S40] C++：查找元素
来源：http://dali.hfpthk.cn/Article/details/gtfbqypxlk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.andypj.xyz/Article/details/gtasyovzum.html

[S41] C++：类与构造函数
来源：http://dali.cdnleiting.top/Article/details/gtmngmsnyk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ehwqpu.com/Article/details/gtmvcyfpuh.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258888.top/Article/details/gtmlgtzcom.html

class B : public Base { public: void f() override {} };
来源：http://dali.jianghu66.top/Article/details/gtkiopepqs.html

[S43] C++：智能指针
来源：http://dali.andypj.xyz/Article/details/gtbdbqfzen.html

auto p = std::make_unique<int>(5);
来源：http://dali.yonumen.top/Article/details/gtvtjclwor.html

[S44] C++：引用传参
来源：http://dali.jinyuanbaomall.cn/Article/details/gthieuxtml.html

void inc(int &x) { ++x; }
来源：http://dali.xylfe.cn/Article/details/gtkapyapas.html

[S45] C++：lambda
来源：http://dali.guowangkeji.top/Article/details/gtbuaaigcf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shangyingyoupin.top/Article/details/gtgvmwdtcz.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtrnescc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsdvgtedo.html

[S47] C++：结构化绑定遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtjajonkjx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.redwolf501.top/Article/details/gtmqukivdn.html

[S48] C++：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gthlfziwlx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258888.top/Article/details/gtwrlvsxdh.html

while (std::getline(in, line)) { }
来源：http://dali.zhengqikj.top/Article/details/gtkyvtpgep.html

[S49] C++：写文件
来源：http://dali.jiagoushi.top/Article/details/gtpuadsurq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.smart0.xyz/Article/details/gtijjrqrsp.html

[S50] C++：格式化数字
来源：http://dali.zhengqikj.top/Article/details/gtklwhmocf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daria6918.cn/Article/details/gthtypaecz.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gtlgxevqnf.html

static_cast<double>(a) / b
来源：http://dali.snrcjt.cn/Article/details/gtamzeyvtc.html

[S52] C++：const 与 noexcept
来源：http://dali.sysykeji.top/Article/details/gtzaokcjqq.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gtfwhwmkvq.html

[S53] C++：移动语义
来源：http://dali.316326.xyz/Article/details/gtcbjlzjrb.html

std::vector<int> w = std::move(v);
来源：http://dali.ehwqpu.com/Article/details/gtdcckfskk.html

[S54] C++：异常处理
来源：http://dali.dashuyun.cn/Article/details/gtsqzdgnfs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ehwqpu.com/Article/details/gtvsorkwks.html

[S55] C++：结构化绑定
来源：http://dali.cdnleiting.top/Article/details/gtzcfgsbfh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gogol.net.cn/Article/details/gtqbbbemhx.html

[S56] C++：optional
来源：http://dali.chenjidiqi.icu/Article/details/gtbxtnnopf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.andypj.xyz/Article/details/gtfdygzauc.html

[S57] C++：编译期常量
来源：http://dali.jinqigfzy.top/Article/details/gtgtadpebx.html

constexpr int N = 10;
来源：http://dali.xuanzx.com/Article/details/gtodjfbfmq.html

[S58] C++：命名空间
来源：http://dali.xinyue.icu/Article/details/gtgivjifsg.html

namespace ns { int f() { return 1; } }
来源：http://dali.yongpay.top/Article/details/gtinvzwstj.html

[S59] C++：静态断言
来源：http://dali.chenlongwang.top/Article/details/gtcqofrnjr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjreuzxic.html

[S60] C++：遍历并删除元素
来源：http://dali.redwolf501.top/Article/details/gteuretdej.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.mhx1999.top/Article/details/gtnvkvgzjn.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtksbpeztr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangtech.top/Article/details/gtshetfpfw.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtkcuoikct.html

[T01] Kotlin：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtjgtkjrow.html

println("Hello")
来源：http://dali.andypj.xyz/Article/details/gtjcwhxbmj.html

[T02] Kotlin：变量
来源：http://dali.yanxiufei.cn/Article/details/gtpaqgzmer.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.haohaochexian.top/Article/details/gtgsrmifjn.html

[T03] Kotlin：字符串模板
来源：http://dali.pengpengdd.cyou/Article/details/gteyclgpdb.html

"值: $b"
来源：http://dali.yongpay.top/Article/details/gtaxgxqxsl.html

[T04] Kotlin：空安全
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsinkwjnt.html

val n: String? = null;  n?.length
来源：http://dali.mhx1999.top/Article/details/gtjeykhzrf.html

[T05] Kotlin：when 表达式
来源：http://dali.gogol.net.cn/Article/details/gtcebllxcm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yangfankeji.com/Article/details/gtccfbfmwk.html

[T06] Kotlin：集合映射
来源：http://dali.yvedp.cn/Article/details/gtmwwxyxzf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gttfhjijlt.html

[T07] Kotlin：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gtbqznjvlc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.316326.xyz/Article/details/gtgddivlcg.html

[T08] Kotlin：数据类
来源：http://dali.aizwys.cn/Article/details/gtyaxujocu.html

data class User(val name: String, val age: Int)
来源：http://dali.iojbl.cn/Article/details/gttzxzukah.html

[T09] Kotlin：扩展函数
来源：http://dali.xziqi.cn/Article/details/gtlrguihtt.html

fun String.exclaim() = this + "!"
来源：http://dali.316326.xyz/Article/details/gtkcshbdez.html

[T10] Kotlin：默认参数
来源：http://dali.jqgfzy.top/Article/details/gtuzukpjyk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuxming.cn/Article/details/gthbcfwlow.html

[T11] Kotlin：协程
来源：http://dali.ybcxt.top/Article/details/gtbztmbyuy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.c1oappe.top/Article/details/gtttmulywd.html

[T12] Kotlin：解构声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiufaudvk.html

val (a, b) = Pair(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gtvyboyvyc.html

[T13] Kotlin：只读 Map
来源：http://dali.yj202588.top/Article/details/gtxjobxuej.html

val m = mapOf("a" to 1)
来源：http://dali.jlsjyb.cn/Article/details/gtegvmrzcz.html

[T14] Kotlin：循环
来源：http://dali.yonumen.top/Article/details/gtenftzutw.html

for (i in 1..10) println(i)
来源：http://dali.quarkkingdee.top/Article/details/gtfztgnzxr.html

[T15] Kotlin：接口
来源：http://dali.yuanzhike.top/Article/details/gtbysdzznt.html

interface Shape { fun area(): Double }
来源：http://dali.aibaodan.cn/Article/details/gtdlffyvjb.html

[T16] Swift：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtoxidgrsj.html

print("Hello")
来源：http://dali.mhx1999.top/Article/details/gtpithwhgc.html

[T17] Swift：变量与常量
来源：http://dali.tanke756.top/Article/details/gtwacwbirn.html

var a = 1;  let b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcamhgjt.html

[T18] Swift：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtxkiycxfc.html

"值: \(b)"
来源：http://dali.dianchejie.cn/Article/details/gtqpzsetpt.html


<!-- 参考信息 -->