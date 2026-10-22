代发 wailian999

esac
来源：http://dali.jinqigufen.top/Article/details/gtctucmzbb.html

[R12] for 遍历文件
来源：http://dali.cqqwz.cn/Article/details/gteicnwhaj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.meibo888.top/Article/details/gttsjlzruu.html

[R13] for 计数循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbcfittkr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxuanxn.top/Article/details/gtifumeizj.html

[R14] C 风格 for
来源：http://dali.andypj.xyz/Article/details/gtivnifyro.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gtvidxyfkh.html

[R15] while 逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gtmvaayavs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gttglqedna.html

[R16] until 等待条件
来源：http://dali.yj20258.top/Article/details/gtuiprxlpx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhkxrxqe.html

[R17] 数组定义与取值
来源：http://dali.pycfn.com/Article/details/gtbkgnrhou.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhiwuduotai.top/Article/details/gtxbfznawr.html

[R18] 遍历数组
来源：http://dali.xylfe.cn/Article/details/gtefgtpwyh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.mhx1999.top/Article/details/gtcjqhbhnk.html

[R19] 数组长度
来源：http://dali.shuidangran.top/Article/details/gtlbtvhqoi.html

echo "${#arr[@]}"
来源：http://dali.hnqzz.top/Article/details/gtchmmwqie.html

[R20] 关联数组（字典）
来源：http://dali.jyoumei.cn/Article/details/gtiunebcny.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ydzc1.top/Article/details/gtjxqkkpak.html

[R21] 字符串长度
来源：http://dali.fzhhl.top/Article/details/gtciuyxyil.html

echo "${#s}"
来源：http://dali.shangyingyoupin.top/Article/details/gtjsbtjbpz.html

[R22] 截取子串
来源：http://dali.ybcxt.top/Article/details/gtfbhtjzph.html

echo "${s:0:5}"
来源：http://dali.jinqigufen.top/Article/details/gtkthghest.html

[R23] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gtzgqkpdxu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fengsongda.top/Article/details/gtpvpenykg.html

[R24] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtekbizomi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dianchejie.cn/Article/details/gtjyehdcwu.html

[R25] 去后缀 / 去前缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqyuxuvi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shuidangran.top/Article/details/gthwihnrsj.html

[R26] 命令替换
来源：http://dali.meibo888.top/Article/details/gtnfcotwwv.html

now=$(date +%F); echo "$now"
来源：http://dali.wangshuangyany.cn/Article/details/gtehkiwjez.html

[R27] 算术展开
来源：http://dali.zdqjudy.top/Article/details/gtajelotoa.html

echo $((1 + 2 * 3))
来源：http://dali.zhixingplan.top/Article/details/gtlsijfscu.html

[R28] 浮点运算
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzybtbarg.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinghuilouyu.cn/Article/details/gtorursatk.html

[R29] 定义函数
来源：http://dali.ybcxt.top/Article/details/gtbtvktiby.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zdqjudy.top/Article/details/gtozihlvgf.html

[R30] 函数返回状态码
来源：http://dali.jlsjyb.cn/Article/details/gtmcbhchdl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigufen.top/Article/details/gtfzzwjvtp.html

[R31] 局部变量
来源：http://dali.cqqwz.cn/Article/details/gthehjebhi.html

f() { local x=1; echo "$x"; }
来源：http://dali.jqgfzy.top/Article/details/gtlbxmnzfb.html

[R32] 参数个数校验
来源：http://dali.redwolf501.top/Article/details/gtzovchnjr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gtuqivgvrj.html

[R33] 捕获错误并提示行号
来源：http://dali.sysykeji.top/Article/details/gtimpnfmqh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gotoacloud.top/Article/details/gtiajnuqjh.html

[R34] 退出时清理
来源：http://dali.guannengcc.top/Article/details/gtyflokbyh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gtmfkpaboz.html

[R35] 后台执行并等待
来源：http://dali.shuidangran.top/Article/details/gtdzsofcdl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgufenzy.top/Article/details/gtlmsehyal.html

[R36] 并发执行多个任务
来源：http://dali.jyoumei.cn/Article/details/gtuuonrsde.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.guannengcc.top/Article/details/gtdmshdldr.html

[R37] 把输出赋给变量
来源：http://dali.ybcxt.top/Article/details/gtyzvbmapj.html

files=$(ls -1)
来源：http://dali.cashguo.top/Article/details/gtkzbmdjnx.html

[R38] 管道串联
来源：http://dali.andypj.xyz/Article/details/gtbrvawkgt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.wangshuangyany.cn/Article/details/gtxwkumtvi.html

[R39] 重定向标准输出与错误
来源：http://dali.sufxvd.cn/Article/details/gtnbzdkjqq.html

cmd > out.log 2>&1
来源：http://dali.xinyue.icu/Article/details/gthzipluda.html

[R40] 追加写日志
来源：http://dali.pycfn.com/Article/details/gtjbpatgnl.html

echo "log" >> out.log
来源：http://dali.redwolf501.top/Article/details/gtwssunaou.html

[R41] 丢弃输出
来源：http://dali.jqgfzy.top/Article/details/gtlsysaptm.html

cmd >/dev/null 2>&1
来源：http://dali.tanke756.top/Article/details/gtbwuvejdf.html

[R42] 输入重定向
来源：http://dali.hywenlv.cn/Article/details/gtbnzpcdtj.html

wc -l < a.txt
来源：http://dali.iojbl.cn/Article/details/gtulqpzqsv.html

[R43] 按名字查找文件
来源：http://dali.c1oappe.top/Article/details/gtykzwbkox.html

find . -name "*.log" -type f
来源：http://dali.vqdsnc.cn/Article/details/gtxbixokjo.html

[R44] 按修改时间查找
来源：http://dali.guannengcc.top/Article/details/gtoepaaavh.html

find . -mtime -7 -type f
来源：http://dali.shuidangran.top/Article/details/gtweeegizv.html

[R45] 批量删除
来源：http://dali.cucudq.cn/Article/details/gtsvrapvef.html

find . -name "*.tmp" -delete
来源：http://dali.zhiwuduotai.top/Article/details/gtcuwcamkt.html

[R46] 递归替换文件内容
来源：http://dali.jinqigfzy.top/Article/details/gtmoebdwtl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigufen.top/Article/details/gtbnnaysmz.html

[R47] sed 单行替换
来源：http://dali.316326.xyz/Article/details/gtcmsjhvmr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shuidangran.top/Article/details/gtdskofylg.html

[R48] awk 取指定列
来源：http://dali.iojbl.cn/Article/details/gtdmqmdtqp.html

awk '{print $1, $3}' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtjvaqfwot.html

[R49] awk 带条件
来源：http://dali.yj202588.top/Article/details/gtvfixmtfk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.birdmap.top/Article/details/gtetittxay.html

[R50] awk 求和
来源：http://dali.tian-w.cn/Article/details/gtueckbklw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gtmnfpmzzu.html

[R51] 排序去重取前几
来源：http://dali.jlsjyb.cn/Article/details/gtpeoyjbfx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daria6918.cn/Article/details/gtvdqwxeyi.html

[R52] 统计行数
来源：http://dali.shuidangran.top/Article/details/gtehihrych.html

wc -l a.txt
来源：http://dali.shzxlz.cn/Article/details/gtykgsjsrx.html

[R53] 查看文件头与实时尾
来源：http://dali.fzhhl.top/Article/details/gtpiyclpql.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shzxlz.cn/Article/details/gtdarslhyz.html

[R54] 比较两个文件
来源：http://dali.guannengcc.top/Article/details/gtcdwetjkb.html

diff a.txt b.txt
来源：http://dali.316326.xyz/Article/details/gtmlcftsdt.html

[R55] 压缩与解压
来源：http://dali.sweek.top/Article/details/gtnsrentye.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jianghu66.top/Article/details/gtbkfcfnsc.html

[R56] 远程拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtdzytnjii.html

scp file user@host:/path/
来源：http://dali.zhiwuduotai.top/Article/details/gthfddrhxq.html

[R57] 远程执行命令
来源：http://dali.tianlin.xyz/Article/details/gtrqnsioca.html

ssh user@host 'uptime'
来源：http://dali.shzxlz.cn/Article/details/gthzypbfay.html

[R58] 下载文件
来源：http://dali.gzhubu.top/Article/details/gtgiwlxkzc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aibaodan.cn/Article/details/gtjsdcggkg.html

[R59] 发 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gtjyqvdoev.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangdashe.top/Article/details/gtlgbvtiff.html

[R60] 只看 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gttquhrhdq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqivugpy.html

[R61] 磁盘占用
来源：http://dali.jianghu66.top/Article/details/gtgdcozauz.html

df -h;  du -sh *
来源：http://dali.iojbl.cn/Article/details/gtonczdzjh.html

[R62] 找最占空间的文件
来源：http://dali.zhengqikj.top/Article/details/gtlwzgyztf.html

du -ah . | sort -rh | head -10
来源：http://dali.nwbrower.top/Article/details/gtfcrripiq.html

[R63] 内存与进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkevmewze.html

free -h;  ps aux | grep nginx
来源：http://dali.ydzc1.top/Article/details/gtmmjtfrui.html

[R64] 结束进程
来源：http://dali.aibaodan.cn/Article/details/gtlodtfxml.html

kill -9 $(pgrep -f app.py)
来源：http://dali.meibo888.top/Article/details/gtbzlphqao.html

[R65] 查看端口占用
来源：http://dali.sweek.top/Article/details/gtebvayhzx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fzhhl.top/Article/details/gtjbemadnv.html

[R66] 定时任务
来源：http://dali.9152youxi.cn/Article/details/gtiwerplos.html

crontab -e;  crontab -l
来源：http://dali.yanxiufei.cn/Article/details/gtrxdujihg.html

[R67] 生成随机十六进制串
来源：http://dali.wangdashe.top/Article/details/gtktsmdzac.html

openssl rand -hex 16
来源：http://dali.ehwqpu.com/Article/details/gtjwwbmxue.html

[R68] 计算文件校验值
来源：http://dali.gaohongyu789.top/Article/details/gtsgaokowa.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yueranfly.top/Article/details/gtxecujrmg.html

[R69] 生成随机密码
来源：http://dali.316326.xyz/Article/details/gtwfmqzekc.html

head -c 16 /dev/urandom | base64
来源：http://dali.hfpthk.cn/Article/details/gtygbgxdpp.html

[R70] 时间戳与互转
来源：http://dali.meibo888.top/Article/details/gtcwyzpxqt.html

date +%s;  date -d @1700000000
来源：http://dali.zycfv.cn/Article/details/gtzoejakmt.html

[R71] 日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gtjbqkcvzc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sufxvd.cn/Article/details/gtskngjtsy.html

[R72] 等待端口就绪
来源：http://dali.nanxuanxn.top/Article/details/gtvxejiijj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tanke756.top/Article/details/gtbaztfyfz.html

[R73] 分割大日志
来源：http://dali.jiagoushi.top/Article/details/gtdwxenxgc.html

split -l 1000 big.log part_
来源：http://dali.yonumen.top/Article/details/gtpjqkrqfy.html

[R74] 批量重命名
来源：http://dali.0kj1m.cn/Article/details/gtueshtgde.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.9152youxi.cn/Article/details/gtvmfbfsnz.html

[R75] 导出环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtdumpqsso.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinqigufen.top/Article/details/gtdbjdomlp.html

[R76] 使用临时文件
来源：http://dali.hongshengwenyu.top/Article/details/gtlttckyis.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gtskukxstm.html

[R77] 读取用户输入
来源：http://dali.chenjidiqi.icu/Article/details/gtxgienjtq.html

read -rp "请输入: " ans
来源：http://dali.cashguo.top/Article/details/gtgjnsilwf.html

[R78] 交互式菜单
来源：http://dali.pengpengdd.cyou/Article/details/gtopwpfjlv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jlsjyb.cn/Article/details/gtyetmgcyh.html

[R79] 解析命令行选项
来源：http://dali.shangyingyoupin.top/Article/details/gtwvlpawhy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gogol.net.cn/Article/details/gtubjjhnzp.html

[R80] 查看脚本执行耗时
来源：http://dali.yueranfly.top/Article/details/gtlkrscghw.html

time ./run.sh
来源：http://dali.jinqigufen.top/Article/details/gtvpydoxsa.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtarevzvog.html

S. C / C++ 专题
来源：http://dali.nanxuanxn.top/Article/details/gtalvzpurg.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtunrficwo.html

[S01] C：Hello World
来源：http://dali.hnqzz.top/Article/details/gtbtlrdcnw.html

#include <stdio.h>
来源：http://dali.jqgufenzy.top/Article/details/gtxtrcjche.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ydzc1.top/Article/details/gthqjiasvd.html

[S02] C：变量与格式化输出
来源：http://dali.cashguo.top/Article/details/gtuvwngeqx.html

int a = 10; printf("%d\n", a);
来源：http://dali.yonumen.top/Article/details/gteptlwpaz.html

[S03] C：读入整数
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxjebnlt.html

int x; scanf("%d", &x);
来源：http://dali.dianchejie.cn/Article/details/gtzzbacwwj.html

[S04] C：字符串复制
来源：http://dali.havefunace.top/Article/details/gtujepojjl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtdbjgmtxt.html

[S05] C：字符串长度
来源：http://dali.zhengqikj.top/Article/details/gtwgxslwdg.html

strlen(s)
来源：http://dali.shzxlz.cn/Article/details/gthofzpftr.html

[S06] C：字符串比较
来源：http://dali.ydzc1.top/Article/details/gtpdonxkty.html

strcmp(a, b) == 0
来源：http://dali.tanke756.top/Article/details/gturgrdaqt.html

[S07] C：数组遍历求和
来源：http://dali.daria6918.cn/Article/details/gteytghkah.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jiagoushi.top/Article/details/gtipuchzog.html

[S08] C：动态内存分配与释放
来源：http://dali.ehwqpu.com/Article/details/gttpwljcqt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daria6918.cn/Article/details/gtuvvdnaep.html

[S09] C：结构体定义与初始化
来源：http://dali.ivvv.top/Article/details/gtiptfrucx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pengpengdd.cyou/Article/details/gtelmvpkdy.html

[S10] C：指针与解引用
来源：http://dali.smart0.xyz/Article/details/gtbluizfyt.html

int *p = &a;  *p = 5;
来源：http://dali.sysykeji.top/Article/details/gtlqvvdfdw.html

[S11] C：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtmoovavqh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhoulong.xyz/Article/details/gttbsurmro.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gtodkzyajc.html

fclose(f);
来源：http://dali.yvedp.cn/Article/details/gtbiasmika.html

[S12] C：写文件
来源：http://dali.chenlongwang.top/Article/details/gtncjhcksr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gtundylmin.html

[S13] C：宏定义
来源：http://dali.9152youxi.cn/Article/details/gtxtdilaan.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmxjzbqc.html

[S14] C：枚举
来源：http://dali.daria6918.cn/Article/details/gtclbpzunl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.haohaochexian.top/Article/details/gtsowrlpbo.html

[S15] C：类型转换
来源：http://dali.svipenyu.cn/Article/details/gtkejevknk.html

(double) a / b
来源：http://dali.ppjwa.cn/Article/details/gtcerbchfl.html

[S16] C：位操作置位
来源：http://dali.havefunace.top/Article/details/gtnsincmfi.html

x |= (1 << 3);
来源：http://dali.yj20258.top/Article/details/gtxzbtzqiq.html

[S17] C：安全拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtqggdubgo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yueranfly.top/Article/details/gtihjihufw.html

[S18] C：命令行参数
来源：http://dali.wangdashe.top/Article/details/gtuelvksae.html

int main(int argc, char **argv)
来源：http://dali.zycfv.cn/Article/details/gtnybuqqwq.html

[S19] C：快速排序
来源：http://dali.havefunace.top/Article/details/gtwpfvdygb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gtokiyosgx.html

[S20] C：二分查找
来源：http://dali.gzhubu.top/Article/details/gtjqavylpr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gtqskmbokw.html

[S21] C：字符类别判断
来源：http://dali.yonumen.top/Article/details/gtahqdatgr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhoulong.xyz/Article/details/gtbevmmaea.html

[S22] C：字符串转数字
来源：http://dali.jlsjyb.cn/Article/details/gtyeifpvpi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.pengpengdd.cyou/Article/details/gtlhwzfoyc.html

[S23] C：随机数
来源：http://dali.jqgufenzy.top/Article/details/gtkeyrkfuz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sxryk.cn/Article/details/gtoztyntyx.html

[S24] C：获取本地时间
来源：http://dali.smart0.xyz/Article/details/gtlhzmpcfx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuanzhike.top/Article/details/gteqwbzuro.html

[S25] C：内存拷贝
来源：http://dali.hfpthk.cn/Article/details/gtpzyrchxf.html

memcpy(dst, src, n);
来源：http://dali.haohaochexian.top/Article/details/gtxrcpqytd.html

[S26] C：内存清零
来源：http://dali.gogol.net.cn/Article/details/gtqaajcuzb.html

memset(a, 0, sizeof a);
来源：http://dali.zhiwuduotai.top/Article/details/gtynkvbbmc.html

[S27] C：定义常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvakybcd.html

const double PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtndqovdqw.html

[S28] C：静态变量
来源：http://dali.cashguo.top/Article/details/gtwsvwktfp.html

static int counter = 0;
来源：http://dali.kuanghao11.cn/Article/details/gtblsgdfoi.html

[S29] C：变参函数
来源：http://dali.jianghu66.top/Article/details/gtpesknfye.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jyoumei.cn/Article/details/gtfpdeavgm.html

[S30] C：头文件保护
来源：http://dali.cheryme.top/Article/details/gtfrhrrmhc.html

#ifndef X_H
来源：http://dali.jianghu66.top/Article/details/gtgvhekgxv.html

#define X_H
来源：http://dali.yanxiufei.cn/Article/details/gtyserhhmt.html

#endif
来源：http://dali.xylfe.cn/Article/details/gtewupnuop.html

[S31] C++：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtqvwaprpf.html

#include <iostream>
来源：http://dali.aizwys.cn/Article/details/gtohrkxxby.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gogol.net.cn/Article/details/gtqpjtikmi.html

[S32] C++：字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzafecfrs.html

std::string s = "hi";  s += "!";
来源：http://dali.guowangkeji.top/Article/details/gtlksxsqbs.html

[S33] C++：vector 增删
来源：http://dali.hysaishi.cn/Article/details/gtdcfqitef.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sxryk.cn/Article/details/gtbbranzhe.html

[S34] C++：遍历 vector
来源：http://dali.aizwys.cn/Article/details/gtevycquwb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gotoacloud.top/Article/details/gtdcchydvg.html

[S35] C++：map
来源：http://dali.9152youxi.cn/Article/details/gtzacnkhoh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gtpjqahtcf.html

[S36] C++：unordered_map
来源：http://dali.sweek.top/Article/details/gtgqxcdjhs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtuqsvrkmt.html

[S37] C++：set
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzdosqlq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tian-w.cn/Article/details/gtiehnfhjh.html

[S38] C++：排序
来源：http://dali.nwbrower.top/Article/details/gttmetczwi.html

std::sort(v.begin(), v.end());
来源：http://dali.fengsongda.top/Article/details/gtnlgapdfo.html

[S39] C++：自定义比较器排序
来源：http://dali.sufxvd.cn/Article/details/gtevmbrdlb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fengsongda.top/Article/details/gtxinkhddt.html

[S40] C++：查找元素
来源：http://dali.xziqi.cn/Article/details/gtnejpjtas.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.9152youxi.cn/Article/details/gtayzsltxt.html

[S41] C++：类与构造函数
来源：http://dali.cqqwz.cn/Article/details/gtcrqmghjc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.redwolf501.top/Article/details/gttldbxzpl.html

[S42] C++：继承与虚函数
来源：http://dali.c1oappe.top/Article/details/gtayafxnqa.html

class B : public Base { public: void f() override {} };
来源：http://dali.dashuyun.cn/Article/details/gtrykjulsh.html

[S43] C++：智能指针
来源：http://dali.snrcjt.cn/Article/details/gtrfkqiyjh.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnxiangtu.top/Article/details/gtmzsznnrw.html

[S44] C++：引用传参
来源：http://dali.sxryk.cn/Article/details/gtbdewlyro.html

void inc(int &x) { ++x; }
来源：http://dali.smart0.xyz/Article/details/gttdrpnovu.html

[S45] C++：lambda
来源：http://dali.ivvv.top/Article/details/gtzngoxywm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinghuilouyu.cn/Article/details/gthnbrnpan.html

[S46] C++：函数模板
来源：http://dali.xziqi.cn/Article/details/gtzymzyqjb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.smart0.xyz/Article/details/gtvjgefcyu.html

[S47] C++：结构化绑定遍历
来源：http://dali.andypj.xyz/Article/details/gtxmljpvps.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fzhhl.top/Article/details/gtymsihzdr.html

[S48] C++：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrqybusu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.snrcjt.cn/Article/details/gtaexjhuoj.html

while (std::getline(in, line)) { }
来源：http://dali.zhongyouzk.top/Article/details/gtpdvbwhxo.html

[S49] C++：写文件
来源：http://dali.xinyue.icu/Article/details/gtktwjrxjg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shzxlz.cn/Article/details/gtetwmkoij.html

[S50] C++：格式化数字
来源：http://dali.guannengcc.top/Article/details/gtvcsuokjn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yongpay.top/Article/details/gthhrxliqn.html

[S51] C++：显式类型转换
来源：http://dali.xuanzx.com/Article/details/gtzzgpesjz.html

static_cast<double>(a) / b
来源：http://dali.jinghuilouyu.cn/Article/details/gtukqwhtnx.html

[S52] C++：const 与 noexcept
来源：http://dali.yongpay.top/Article/details/gtvrpyzoua.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258888.top/Article/details/gtsikqifhi.html

[S53] C++：移动语义
来源：http://dali.hysaishi.cn/Article/details/gtcminakyw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhengqikj.top/Article/details/gtqxzvkxwd.html

[S54] C++：异常处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvhycyph.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuanzhike.top/Article/details/gtuqwkoqog.html

[S55] C++：结构化绑定
来源：http://dali.bjfxy.top/Article/details/gtuwxawruy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tanke756.top/Article/details/gtprjwyjxz.html

[S56] C++：optional
来源：http://dali.ehwqpu.com/Article/details/gtlrybxjgc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkghjwdhi.html

[S57] C++：编译期常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmjznumn.html

constexpr int N = 10;
来源：http://dali.c1oappe.top/Article/details/gtdnhfievf.html

[S58] C++：命名空间
来源：http://dali.tian-w.cn/Article/details/gtiaczoazz.html

namespace ns { int f() { return 1; } }
来源：http://dali.aibaodan.cn/Article/details/gtmpagskyt.html

[S59] C++：静态断言
来源：http://dali.yj202588.top/Article/details/gtxnwnzzzy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ydzc1.top/Article/details/gtsmdogvzv.html

[S60] C++：遍历并删除元素
来源：http://dali.guannengcc.top/Article/details/gtvfthljqe.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigufen.top/Article/details/gtnwrqxooe.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtzcmcnhon.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sufxvd.cn/Article/details/gtxzjpmxqo.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtvkucdxzw.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gttwncvsjm.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gthcwvkuyq.html

[T02] Kotlin：变量
来源：http://dali.jqgfzy.top/Article/details/gtineenhvy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yonumen.top/Article/details/gtudkljblw.html

[T03] Kotlin：字符串模板
来源：http://dali.xinyue.icu/Article/details/gtapqltdxy.html

"值: $b"
来源：http://dali.andypj.xyz/Article/details/gtibfimayu.html

[T04] Kotlin：空安全
来源：http://dali.yongpay.top/Article/details/gthpkdexyr.html

val n: String? = null;  n?.length
来源：http://dali.xinyue.icu/Article/details/gtahisokjv.html

[T05] Kotlin：when 表达式
来源：http://dali.zhongyouzk.top/Article/details/gtamdfdqbj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.haohaochexian.top/Article/details/gtmddptord.html

[T06] Kotlin：集合映射
来源：http://dali.iojbl.cn/Article/details/gtzxrevtbk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtfifokuuc.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gttqetfwdh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.meibo888.top/Article/details/gtwwoahiyu.html

[T08] Kotlin：数据类
来源：http://dali.yj20258888.top/Article/details/gtgzlxjbpy.html

data class User(val name: String, val age: Int)
来源：http://dali.zhixingplan.top/Article/details/gtwkiakwgg.html

[T09] Kotlin：扩展函数
来源：http://dali.jqgfzy.top/Article/details/gtohujzulh.html

fun String.exclaim() = this + "!"
来源：http://dali.yueranfly.top/Article/details/gttovzqyuh.html

[T10] Kotlin：默认参数
来源：http://dali.chenlongwang.top/Article/details/gtfaunprct.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuanzhike.top/Article/details/gtoxzzlddh.html

[T11] Kotlin：协程
来源：http://dali.fengsongda.top/Article/details/gttwsvefnp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zdqjudy.top/Article/details/gtlvkmejgz.html

[T12] Kotlin：解构声明
来源：http://dali.yanxiufei.cn/Article/details/gtsroapobm.html

val (a, b) = Pair(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gtzlrjendy.html

[T13] Kotlin：只读 Map
来源：http://dali.yuxming.cn/Article/details/gtdiemebeo.html

val m = mapOf("a" to 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtltferycj.html

[T14] Kotlin：循环
来源：http://dali.shzxlz.cn/Article/details/gtienhwsyl.html

for (i in 1..10) println(i)
来源：http://dali.tanke756.top/Article/details/gtjgzmepgq.html


<!-- 参考信息 -->