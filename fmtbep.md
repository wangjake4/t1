代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenzaomai.com/Article/details/gtwzyyymbo.html

[R24] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gtvcfsbypu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.kuanghao11.cn/Article/details/gtoekprjir.html

[R25] 去后缀 / 去前缀
来源：http://dali.yueranfly.top/Article/details/gtbavmkrxh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sysykeji.top/Article/details/gthulimsuc.html

[R26] 命令替换
来源：http://dali.zdqjudy.top/Article/details/gtepqvellc.html

now=$(date +%F); echo "$now"
来源：http://dali.svipenyu.cn/Article/details/gtdiohzcsi.html

[R27] 算术展开
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoozaanjr.html

echo $((1 + 2 * 3))
来源：http://dali.cashguo.top/Article/details/gtilmscwsu.html

[R28] 浮点运算
来源：http://dali.ivvv.top/Article/details/gtxzkxovpo.html

echo "scale=2; 10/3" | bc
来源：http://dali.quarkkingdee.top/Article/details/gtyirnjidt.html

[R29] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gtvjofzjug.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ppjwa.cn/Article/details/gtwepwexww.html

[R30] 函数返回状态码
来源：http://dali.jqgufenzy.top/Article/details/gtieltkyvm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.haohaochexian.top/Article/details/gtglmsviie.html

[R31] 局部变量
来源：http://dali.birdmap.top/Article/details/gtbkehskiv.html

f() { local x=1; echo "$x"; }
来源：http://dali.dianchejie.cn/Article/details/gtfvecsacm.html

[R32] 参数个数校验
来源：http://dali.cheryme.top/Article/details/gtwfrbrgid.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gtbngdqnxa.html

[R33] 捕获错误并提示行号
来源：http://dali.xziqi.cn/Article/details/gtfmrsvrgk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shuidangran.top/Article/details/gtirpshsyh.html

[R34] 退出时清理
来源：http://dali.sweek.top/Article/details/gtmwltyfgz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gtndapownp.html

[R35] 后台执行并等待
来源：http://dali.sweek.top/Article/details/gtdgcpfznx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.haohaochexian.top/Article/details/gtunaqrplb.html

[R36] 并发执行多个任务
来源：http://dali.chenjidiqi.icu/Article/details/gtalmlhtwy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.iojbl.cn/Article/details/gtchamzyhl.html

[R37] 把输出赋给变量
来源：http://dali.xuanzx.com/Article/details/gtuojadsxw.html

files=$(ls -1)
来源：http://dali.hywenlv.cn/Article/details/gtjygegpxt.html

[R38] 管道串联
来源：http://dali.andypj.xyz/Article/details/gtmcnvwhuh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xuanzx.com/Article/details/gthssbewjn.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigfzy.top/Article/details/gtrhunabxi.html

cmd > out.log 2>&1
来源：http://dali.cheryme.top/Article/details/gtthanapxd.html

[R40] 追加写日志
来源：http://dali.shangyingyoupin.top/Article/details/gtndmcqtfj.html

echo "log" >> out.log
来源：http://dali.yuanzhike.top/Article/details/gteeywkred.html

[R41] 丢弃输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclokaeuq.html

cmd >/dev/null 2>&1
来源：http://dali.hammf.cn/Article/details/gtzipwdmfd.html

[R42] 输入重定向
来源：http://dali.cheryme.top/Article/details/gtrhiflwuo.html

wc -l < a.txt
来源：http://dali.cqqwz.cn/Article/details/gtfbndraue.html

[R43] 按名字查找文件
来源：http://dali.jlsjyb.cn/Article/details/gtiksbpqvj.html

find . -name "*.log" -type f
来源：http://dali.xylfe.cn/Article/details/gtmtllycae.html

[R44] 按修改时间查找
来源：http://dali.daria6918.cn/Article/details/gtpgscuybp.html

find . -mtime -7 -type f
来源：http://dali.cqqwz.cn/Article/details/gtdizawaaj.html

[R45] 批量删除
来源：http://dali.guowangkeji.top/Article/details/gtkgrnuljt.html

find . -name "*.tmp" -delete
来源：http://dali.hywenlv.cn/Article/details/gtmynevqcd.html

[R46] 递归替换文件内容
来源：http://dali.zhiwuduotai.top/Article/details/gtvejpcawk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuanzx.com/Article/details/gtqpvmxeev.html

[R47] sed 单行替换
来源：http://dali.ydzc1.top/Article/details/gtlvqofjqi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258.top/Article/details/gthcybdqar.html

[R48] awk 取指定列
来源：http://dali.nanxuanxn.top/Article/details/gtxizgrtih.html

awk '{print $1, $3}' a.txt
来源：http://dali.pycfn.com/Article/details/gtuivrxymm.html

[R49] awk 带条件
来源：http://dali.hysaishi.cn/Article/details/gtuocsnbvd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cheryme.top/Article/details/gtkroungnr.html

[R50] awk 求和
来源：http://dali.mhx1999.top/Article/details/gtqneexogw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ybcxt.top/Article/details/gtwdjnnnyu.html

[R51] 排序去重取前几
来源：http://dali.chenlongwang.top/Article/details/gtxfolvxxp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhiwuduotai.top/Article/details/gtlajvegnr.html

[R52] 统计行数
来源：http://dali.xinyue.icu/Article/details/gtptomofvs.html

wc -l a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtdbkyqymj.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigufen.top/Article/details/gtxbxqkayv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenzaomai.com/Article/details/gtrxcdzbvg.html

[R54] 比较两个文件
来源：http://dali.gaohongyu789.top/Article/details/gtvohseqyd.html

diff a.txt b.txt
来源：http://dali.shzxlz.cn/Article/details/gtaawmmtzm.html

[R55] 压缩与解压
来源：http://dali.sysykeji.top/Article/details/gttepaxulk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnmwnnah.html

[R56] 远程拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gtfhvodubr.html

scp file user@host:/path/
来源：http://dali.jianghu66.top/Article/details/gtifnzwksb.html

[R57] 远程执行命令
来源：http://dali.hongshengwenyu.top/Article/details/gtfizppnsf.html

ssh user@host 'uptime'
来源：http://dali.zhengqikj.top/Article/details/gtnznqlqpb.html

[R58] 下载文件
来源：http://dali.zhoulong.xyz/Article/details/gtbkqirfju.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.smart0.xyz/Article/details/gtseixqhok.html

[R59] 发 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gtheltbypx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ppjwa.cn/Article/details/gteembppbi.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gthcoprrtv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhixingplan.top/Article/details/gtbicdgqyz.html

[R61] 磁盘占用
来源：http://dali.0kj1m.cn/Article/details/gttkklerhr.html

df -h;  du -sh *
来源：http://dali.yongpay.top/Article/details/gtyoczfnli.html

[R62] 找最占空间的文件
来源：http://dali.hnqzz.top/Article/details/gtfxurxdgt.html

du -ah . | sort -rh | head -10
来源：http://dali.cdnleiting.top/Article/details/gtojdglvvd.html

[R63] 内存与进程
来源：http://dali.zhiwuduotai.top/Article/details/gtgmclppqt.html

free -h;  ps aux | grep nginx
来源：http://dali.pycfn.com/Article/details/gtjrfszqsp.html

[R64] 结束进程
来源：http://dali.cqqwz.cn/Article/details/gtxnayzevf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258.top/Article/details/gtolhxuzlo.html

[R65] 查看端口占用
来源：http://dali.ivvv.top/Article/details/gtnudkleha.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yonumen.top/Article/details/gttqsunzgn.html

[R66] 定时任务
来源：http://dali.yonumen.top/Article/details/gtvaaufpwu.html

crontab -e;  crontab -l
来源：http://dali.havefunace.top/Article/details/gtfpjugtja.html

[R67] 生成随机十六进制串
来源：http://dali.zhixingplan.top/Article/details/gtisoozqgx.html

openssl rand -hex 16
来源：http://dali.quarkkingdee.top/Article/details/gtrsgrhvwl.html

[R68] 计算文件校验值
来源：http://dali.smart0.xyz/Article/details/gtpuvubkij.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtaxtlboet.html

[R69] 生成随机密码
来源：http://dali.hnqzz.top/Article/details/gtytvpotge.html

head -c 16 /dev/urandom | base64
来源：http://dali.cqqwz.cn/Article/details/gthcmagrnk.html

[R70] 时间戳与互转
来源：http://dali.9152youxi.cn/Article/details/gttqgpxuxz.html

date +%s;  date -d @1700000000
来源：http://dali.xziqi.cn/Article/details/gtrujwmovc.html

[R71] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gtkmymhlay.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.c1oappe.top/Article/details/gttditpcow.html

[R72] 等待端口就绪
来源：http://dali.yangfankeji.com/Article/details/gtdxuawrkh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gtvftbhkoj.html

[R73] 分割大日志
来源：http://dali.cdnleiting.top/Article/details/gtthdcjmhk.html

split -l 1000 big.log part_
来源：http://dali.birdmap.top/Article/details/gtpqbksjal.html

[R74] 批量重命名
来源：http://dali.316326.xyz/Article/details/gtuxhuoyee.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jianghu66.top/Article/details/gtarxzfneh.html

[R75] 导出环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbveommv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yonumen.top/Article/details/gthczoqxuj.html

[R76] 使用临时文件
来源：http://dali.mhx1999.top/Article/details/gtktjatoxp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gtifotnrlz.html

[R77] 读取用户输入
来源：http://dali.cucudq.cn/Article/details/gtogxcmuik.html

read -rp "请输入: " ans
来源：http://dali.haohaochexian.top/Article/details/gtyqxwwgbo.html

[R78] 交互式菜单
来源：http://dali.zdqjudy.top/Article/details/gtjrxwmobc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zycfv.cn/Article/details/gtqevehtqd.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrxezxdh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gaohongyu789.top/Article/details/gtjpbiofcp.html

[R80] 查看脚本执行耗时
来源：http://dali.fengsongda.top/Article/details/gthsxpvunr.html

time ./run.sh
来源：http://dali.yuanzhike.top/Article/details/gtrefybytc.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gthiugwazw.html

S. C / C++ 专题
来源：http://dali.nanxuanxn.top/Article/details/gtrmwodkco.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtoxygqwxb.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gtsiisqydd.html

#include <stdio.h>
来源：http://dali.jlsjyb.cn/Article/details/gtlrzaktwo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zycfv.cn/Article/details/gtbvessngg.html

[S02] C：变量与格式化输出
来源：http://dali.xylfe.cn/Article/details/gtohrtqxyv.html

int a = 10; printf("%d\n", a);
来源：http://dali.shzxlz.cn/Article/details/gtqimavcqo.html

[S03] C：读入整数
来源：http://dali.yuxming.cn/Article/details/gtjalcqbkn.html

int x; scanf("%d", &x);
来源：http://dali.chenzaomai.com/Article/details/gtyeepvyhv.html

[S04] C：字符串复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaedvkqwo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guannengcc.top/Article/details/gtyysszfai.html

[S05] C：字符串长度
来源：http://dali.mhx1999.top/Article/details/gtrvagruuc.html

strlen(s)
来源：http://dali.ydzc1.top/Article/details/gthepqlixl.html

[S06] C：字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjyybxnbj.html

strcmp(a, b) == 0
来源：http://dali.sysykeji.top/Article/details/gtxcormesx.html

[S07] C：数组遍历求和
来源：http://dali.c1oappe.top/Article/details/gtnpcsihem.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangshuangyany.cn/Article/details/gtvwyhcsxw.html

[S08] C：动态内存分配与释放
来源：http://dali.xuetiantiany.cn/Article/details/gtpbwtjzeh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sysykeji.top/Article/details/gthorjkwpa.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gtjbqsfjhj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ivvv.top/Article/details/gtlcodnflf.html

[S10] C：指针与解引用
来源：http://dali.yuanzhike.top/Article/details/gtxtrugsey.html

int *p = &a;  *p = 5;
来源：http://dali.andypj.xyz/Article/details/gtqdexoiyn.html

[S11] C：逐行读文件
来源：http://dali.pycfn.com/Article/details/gtxxmyxthr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinqigufen.top/Article/details/gtvnlruskm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sysykeji.top/Article/details/gtrylsazgf.html

fclose(f);
来源：http://dali.sxryk.cn/Article/details/gtxtlprwep.html

[S12] C：写文件
来源：http://dali.ybcxt.top/Article/details/gthjbylqdr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gtpbpeawyo.html

[S13] C：宏定义
来源：http://dali.nanxinkj.top/Article/details/gtwowqmcjn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nwbrower.top/Article/details/gtooizztar.html

[S14] C：枚举
来源：http://dali.chenlongwang.top/Article/details/gtccsywpyj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sxryk.cn/Article/details/gtjyjcwtrt.html

[S15] C：类型转换
来源：http://dali.dashuyun.cn/Article/details/gtjwomfgpl.html

(double) a / b
来源：http://dali.shzxlz.cn/Article/details/gttjyyljfm.html

[S16] C：位操作置位
来源：http://dali.haohaochexian.top/Article/details/gtfumocure.html

x |= (1 << 3);
来源：http://dali.yj202588.top/Article/details/gtcrwsobrq.html

[S17] C：安全拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtsljzwzgm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmuklppvf.html

[S18] C：命令行参数
来源：http://dali.ybcxt.top/Article/details/gtswxwyycm.html

int main(int argc, char **argv)
来源：http://dali.bjfxy.top/Article/details/gtiodgtmbc.html

[S19] C：快速排序
来源：http://dali.bjfxy.top/Article/details/gtwwkmufif.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sufxvd.cn/Article/details/gtlzcnpgzy.html

[S20] C：二分查找
来源：http://dali.yonumen.top/Article/details/gtuuslwrou.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.pycfn.com/Article/details/gtpkpgutii.html

[S21] C：字符类别判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbrbaxwx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shangyingyoupin.top/Article/details/gtefxogqrx.html

[S22] C：字符串转数字
来源：http://dali.hongshengwenyu.top/Article/details/gtdlgehbqd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.havefunace.top/Article/details/gtkojrzgei.html

[S23] C：随机数
来源：http://dali.xuanzx.com/Article/details/gtebuprwyw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daxiang520.top/Article/details/gttgaotlbo.html

[S24] C：获取本地时间
来源：http://dali.daria6918.cn/Article/details/gtucxxlkfd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.meibo888.top/Article/details/gtutkbplce.html

[S25] C：内存拷贝
来源：http://dali.iojbl.cn/Article/details/gtengrhuwh.html

memcpy(dst, src, n);
来源：http://dali.meibo888.top/Article/details/gthptjwdzl.html

[S26] C：内存清零
来源：http://dali.quarkkingdee.top/Article/details/gtfadxrjis.html

memset(a, 0, sizeof a);
来源：http://dali.xuanzx.com/Article/details/gtdwvupwbz.html

[S27] C：定义常量
来源：http://dali.gaohongyu789.top/Article/details/gtrrotmenx.html

const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtwrgeugyu.html

[S28] C：静态变量
来源：http://dali.yj20258.top/Article/details/gtfuwhjkev.html

static int counter = 0;
来源：http://dali.aibaodan.cn/Article/details/gtznknyqpj.html

[S29] C：变参函数
来源：http://dali.nwbrower.top/Article/details/gtjlegelfv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenlongwang.top/Article/details/gtimqkjcwv.html

[S30] C：头文件保护
来源：http://dali.jinqigfzy.top/Article/details/gtwxoufovx.html

#ifndef X_H
来源：http://dali.quarkkingdee.top/Article/details/gtjvtmidln.html

#define X_H
来源：http://dali.cheryme.top/Article/details/gtsphrjzjg.html

#endif
来源：http://dali.nwbrower.top/Article/details/gtbgvmbapj.html

[S31] C++：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gthntlaqlz.html

#include <iostream>
来源：http://dali.zhixingplan.top/Article/details/gtqrpegquh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigfzy.top/Article/details/gtyhsrwrhg.html

[S32] C++：字符串
来源：http://dali.c1oappe.top/Article/details/gtwzekhnmf.html

std::string s = "hi";  s += "!";
来源：http://dali.mhx1999.top/Article/details/gtgivxtfia.html

[S33] C++：vector 增删
来源：http://dali.shuidangran.top/Article/details/gtlsqvgjab.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgfzy.top/Article/details/gtpwngfuev.html

[S34] C++：遍历 vector
来源：http://dali.guannengcc.top/Article/details/gtmhohborw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.c1oappe.top/Article/details/gtdjrpwtrg.html

[S35] C++：map
来源：http://dali.cashguo.top/Article/details/gtsxkvinbj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtpwigxenj.html

[S36] C++：unordered_map
来源：http://dali.sufxvd.cn/Article/details/gtfvkcyybu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtuypjicsj.html

[S37] C++：set
来源：http://dali.chenzaomai.com/Article/details/gtfztscexd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sxryk.cn/Article/details/gtaaqeaudq.html

[S38] C++：排序
来源：http://dali.xinyue.icu/Article/details/gtukhnlpba.html

std::sort(v.begin(), v.end());
来源：http://dali.andypj.xyz/Article/details/gthuafadnz.html

[S39] C++：自定义比较器排序
来源：http://dali.tanke756.top/Article/details/gthdunppju.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ybcxt.top/Article/details/gthnmlvggt.html

[S40] C++：查找元素
来源：http://dali.vqdsnc.cn/Article/details/gtcybvlgxp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenlongwang.top/Article/details/gtmfirpuqv.html

[S41] C++：类与构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gteybpdkah.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tianlin.xyz/Article/details/gtxscpnnzt.html

[S42] C++：继承与虚函数
来源：http://dali.jiagoushi.top/Article/details/gtluezocng.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gtdmpyhnow.html

[S43] C++：智能指针
来源：http://dali.kuanghao11.cn/Article/details/gtsnnhbgow.html

auto p = std::make_unique<int>(5);
来源：http://dali.xinyue.icu/Article/details/gtznhbxxhm.html

[S44] C++：引用传参
来源：http://dali.jiagoushi.top/Article/details/gtwbyswrvx.html

void inc(int &x) { ++x; }
来源：http://dali.andypj.xyz/Article/details/gtfplnamlv.html

[S45] C++：lambda
来源：http://dali.gotoacloud.top/Article/details/gtqgthqoru.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zdqjudy.top/Article/details/gtleczsrri.html

[S46] C++：函数模板
来源：http://dali.mhx1999.top/Article/details/gtyzwjervu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.redwolf501.top/Article/details/gtzyatbxlv.html

[S47] C++：结构化绑定遍历
来源：http://dali.xziqi.cn/Article/details/gtrrntzzec.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhengqikj.top/Article/details/gtpufcumjp.html

[S48] C++：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtiklmqksn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthspvikir.html

while (std::getline(in, line)) { }
来源：http://dali.pycfn.com/Article/details/gtqflctrmf.html

[S49] C++：写文件
来源：http://dali.daxiang520.top/Article/details/gtfpwrjvhf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gogol.net.cn/Article/details/gtbdoacncl.html

[S50] C++：格式化数字
来源：http://dali.sweek.top/Article/details/gtlxvvvild.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.iojbl.cn/Article/details/gteycqmbpc.html

[S51] C++：显式类型转换
来源：http://dali.yueranfly.top/Article/details/gthmucmzvv.html

static_cast<double>(a) / b
来源：http://dali.vqdsnc.cn/Article/details/gtwoqilxaa.html

[S52] C++：const 与 noexcept
来源：http://dali.yj20258888.top/Article/details/gtzflckmxh.html

int size() const noexcept { return n_; }
来源：http://dali.quarkkingdee.top/Article/details/gthiwvjlzh.html

[S53] C++：移动语义
来源：http://dali.fengsongda.top/Article/details/gtakkabgok.html

std::vector<int> w = std::move(v);
来源：http://dali.zycfv.cn/Article/details/gtzcsxfvrm.html

[S54] C++：异常处理
来源：http://dali.0kj1m.cn/Article/details/gtraiajjod.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jqgfzy.top/Article/details/gtdobygoiu.html

[S55] C++：结构化绑定
来源：http://dali.bjfxy.top/Article/details/gtcessbtdh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwiqfokf.html

[S56] C++：optional
来源：http://dali.gzhubu.top/Article/details/gtyhtnfcnh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj202588.top/Article/details/gtcqwylpjz.html

[S57] C++：编译期常量
来源：http://dali.guowangkeji.top/Article/details/gtgqamzrrl.html

constexpr int N = 10;
来源：http://dali.cheryme.top/Article/details/gtrmizuzol.html

[S58] C++：命名空间
来源：http://dali.nanxinkj.top/Article/details/gtgetqgyri.html

namespace ns { int f() { return 1; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtqxtalgcw.html

[S59] C++：静态断言
来源：http://dali.yuxming.cn/Article/details/gtuuuzerup.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pycfn.com/Article/details/gttcfxcwqo.html

[S60] C++：遍历并删除元素
来源：http://dali.chenjidiqi.icu/Article/details/gtexfrzfyk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cheryme.top/Article/details/gtvceslylt.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtdhqbtzat.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tanke756.top/Article/details/gtdiicfmff.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtycptjbha.html

[T01] Kotlin：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtszkcqgvk.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtetnqhzyj.html

[T02] Kotlin：变量
来源：http://dali.jiagoushi.top/Article/details/gtpmipbzpz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangshuangyany.cn/Article/details/gtevmqnfhy.html

[T03] Kotlin：字符串模板
来源：http://dali.hnxiangtu.top/Article/details/gtqvhcmtcp.html

"值: $b"
来源：http://dali.yueranfly.top/Article/details/gtkxkdlkbg.html

[T04] Kotlin：空安全
来源：http://dali.guowangkeji.top/Article/details/gtzjthjwiu.html

val n: String? = null;  n?.length
来源：http://dali.wangshuangyany.cn/Article/details/gtlxgsmugt.html

[T05] Kotlin：when 表达式
来源：http://dali.havefunace.top/Article/details/gtohvxqdvz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoczyuwyn.html

[T06] Kotlin：集合映射
来源：http://dali.chenlongwang.top/Article/details/gtuwvaabjm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sxryk.cn/Article/details/gtpfihnoov.html

[T07] Kotlin：集合过滤
来源：http://dali.yangfankeji.com/Article/details/gtrxezxxyy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenjidiqi.icu/Article/details/gtkzxvnbtc.html

[T08] Kotlin：数据类
来源：http://dali.ivvv.top/Article/details/gtpggjxzhk.html

data class User(val name: String, val age: Int)
来源：http://dali.tian-w.cn/Article/details/gtywymwpqc.html

[T09] Kotlin：扩展函数
来源：http://dali.0kj1m.cn/Article/details/gtwkpqzvsd.html

fun String.exclaim() = this + "!"
来源：http://dali.xuanzx.com/Article/details/gtnzpudojr.html

[T10] Kotlin：默认参数
来源：http://dali.nanxinkj.top/Article/details/gtbjdnxser.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuanzhike.top/Article/details/gtpcpfpypt.html

[T11] Kotlin：协程
来源：http://dali.hfpthk.cn/Article/details/gtrsopprxj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fzhhl.top/Article/details/gtcrglesue.html

[T12] Kotlin：解构声明
来源：http://dali.hnxiangtu.top/Article/details/gtuxadwpay.html

val (a, b) = Pair(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gtwojnbdqi.html

[T13] Kotlin：只读 Map
来源：http://dali.pengpengdd.cyou/Article/details/gtuchlgcjy.html

val m = mapOf("a" to 1)
来源：http://dali.smart0.xyz/Article/details/gtgmhljwou.html

[T14] Kotlin：循环
来源：http://dali.yuxming.cn/Article/details/gthtgsiwby.html

for (i in 1..10) println(i)
来源：http://dali.cheryme.top/Article/details/gtekekqvhq.html

[T15] Kotlin：接口
来源：http://dali.hongshengwenyu.top/Article/details/gtiipyjhgm.html

interface Shape { fun area(): Double }
来源：http://dali.jyoumei.cn/Article/details/gtxbdcgcnk.html

[T16] Swift：Hello World
来源：http://dali.ydzc1.top/Article/details/gtouflvieg.html

print("Hello")
来源：http://dali.hammf.cn/Article/details/gtmxkhixsr.html

[T17] Swift：变量与常量
来源：http://dali.yonumen.top/Article/details/gttbvnzpwv.html

var a = 1;  let b = 2
来源：http://dali.gotoacloud.top/Article/details/gtvaszbmrr.html

[T18] Swift：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtbwyrqpel.html

"值: \(b)"
来源：http://dali.aibaodan.cn/Article/details/gtzgydxojk.html

[T19] Swift：可选绑定
来源：http://dali.ydzc1.top/Article/details/gtyrrxhaiw.html

if let n = opt { print(n) }
来源：http://dali.zhengqikj.top/Article/details/gtmydjyhln.html

[T20] Swift：数组操作
来源：http://dali.hfpthk.cn/Article/details/gtgtlozoxr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.aibaodan.cn/Article/details/gtkxdcultw.html

[T21] Swift：遍历
来源：http://dali.redwolf501.top/Article/details/gtatwzljhd.html

for x in a { print(x) }
来源：http://dali.gotoacloud.top/Article/details/gtvhurwcbp.html

[T22] Swift：字典
来源：http://dali.hnxiangtu.top/Article/details/gthybyfetq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtswqwifon.html

[T23] Swift：函数
来源：http://dali.ydzc1.top/Article/details/gtkkdmiqth.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gtmnljyruh.html

[T24] Swift：闭包
来源：http://dali.ybcxt.top/Article/details/gtkdmpkecj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gthlrkegtb.html

[T25] Swift：结构体
来源：http://dali.sxryk.cn/Article/details/gtepabnyta.html

struct P { var x: Int }
来源：http://dali.sysykeji.top/Article/details/gtosdhxiun.html

[T26] Swift：类与重写
来源：http://dali.xinyue.icu/Article/details/gtyjiuwtzr.html

class A: Base { override func f() {} }
来源：http://dali.9152youxi.cn/Article/details/gtrmakmgxr.html


<!-- 参考信息 -->