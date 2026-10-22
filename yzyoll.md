代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gtghqrkjhm.html

[R14] C 风格 for
来源：http://dali.jianghu66.top/Article/details/gtllyiqpyl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gtcegkzyix.html

[R15] while 逐行读文件
来源：http://dali.ivvv.top/Article/details/gthdsyvxfc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.mhx1999.top/Article/details/gtgcifdopv.html

[R16] until 等待条件
来源：http://dali.mhx1999.top/Article/details/gtcijmvcre.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gthzhmofal.html

[R17] 数组定义与取值
来源：http://dali.dashuyun.cn/Article/details/gtdxasevtb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtdnhrlpdm.html

[R18] 遍历数组
来源：http://dali.hammf.cn/Article/details/gthfxyecmc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.andypj.xyz/Article/details/gtvbzaynqe.html

[R19] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gtxtclukeo.html

echo "${#arr[@]}"
来源：http://dali.guowangkeji.top/Article/details/gtynxljfqm.html

[R20] 关联数组（字典）
来源：http://dali.dashuyun.cn/Article/details/gtqybtmlhp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtfucqomsc.html

[R21] 字符串长度
来源：http://dali.redwolf501.top/Article/details/gtixmirzjt.html

echo "${#s}"
来源：http://dali.zhixingplan.top/Article/details/gtcogplpoj.html

[R22] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gtdkjdjosk.html

echo "${s:0:5}"
来源：http://dali.redwolf501.top/Article/details/gtyhkrucpf.html

[R23] 字符串替换
来源：http://dali.yj202588.top/Article/details/gtxfghbzbq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.meibo888.top/Article/details/gtayqsekbf.html

[R24] 大小写转换
来源：http://dali.yonumen.top/Article/details/gtizhciiuk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zdqjudy.top/Article/details/gtnmqzzgdh.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuetiantiany.cn/Article/details/gtbbvpmtqz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuxming.cn/Article/details/gtfaislktf.html

[R26] 命令替换
来源：http://dali.sufxvd.cn/Article/details/gtnirmfojr.html

now=$(date +%F); echo "$now"
来源：http://dali.hongshengwenyu.top/Article/details/gtpsjrwwiu.html

[R27] 算术展开
来源：http://dali.meibo888.top/Article/details/gtcjwjdjux.html

echo $((1 + 2 * 3))
来源：http://dali.quarkkingdee.top/Article/details/gtpmjpirxg.html

[R28] 浮点运算
来源：http://dali.9152youxi.cn/Article/details/gtwrtesgsl.html

echo "scale=2; 10/3" | bc
来源：http://dali.xziqi.cn/Article/details/gtptdukgvi.html

[R29] 定义函数
来源：http://dali.yongpay.top/Article/details/gtgzajqcji.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenjidiqi.icu/Article/details/gttyecenyo.html

[R30] 函数返回状态码
来源：http://dali.birdmap.top/Article/details/gtgxwqefwr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.0kj1m.cn/Article/details/gtzxhjzgzg.html

[R31] 局部变量
来源：http://dali.nwbrower.top/Article/details/gtjekafioy.html

f() { local x=1; echo "$x"; }
来源：http://dali.birdmap.top/Article/details/gtcoakpskv.html

[R32] 参数个数校验
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzxrkdyn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtilktunnd.html

[R33] 捕获错误并提示行号
来源：http://dali.sufxvd.cn/Article/details/gtqpuajtpf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.iojbl.cn/Article/details/gtinufcqqx.html

[R34] 退出时清理
来源：http://dali.jqgfzy.top/Article/details/gtwpvtkciy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gtuznyvguo.html

[R35] 后台执行并等待
来源：http://dali.yj20258888.top/Article/details/gtyqruhvcf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daria6918.cn/Article/details/gtgwmimomr.html

[R36] 并发执行多个任务
来源：http://dali.svipenyu.cn/Article/details/gtetbywhmv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zycfv.cn/Article/details/gttjniaslx.html

[R37] 把输出赋给变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibjklpnx.html

files=$(ls -1)
来源：http://dali.yanxiufei.cn/Article/details/gtfrbqdqsk.html

[R38] 管道串联
来源：http://dali.tian-w.cn/Article/details/gthogrdmub.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yonumen.top/Article/details/gtsfgbzbye.html

[R39] 重定向标准输出与错误
来源：http://dali.guannengcc.top/Article/details/gttlmzynin.html

cmd > out.log 2>&1
来源：http://dali.zdqjudy.top/Article/details/gtqhqfeidn.html

[R40] 追加写日志
来源：http://dali.pycfn.com/Article/details/gtbrmkobpo.html

echo "log" >> out.log
来源：http://dali.yongpay.top/Article/details/gthtepssxu.html

[R41] 丢弃输出
来源：http://dali.gzhubu.top/Article/details/gtgfdmtxkf.html

cmd >/dev/null 2>&1
来源：http://dali.svipenyu.cn/Article/details/gtnlcopxxn.html

[R42] 输入重定向
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulbavche.html

wc -l < a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtvxosuclw.html

[R43] 按名字查找文件
来源：http://dali.hongshengwenyu.top/Article/details/gtpppvoego.html

find . -name "*.log" -type f
来源：http://dali.hysaishi.cn/Article/details/gtzuatjyzp.html

[R44] 按修改时间查找
来源：http://dali.tanke756.top/Article/details/gtkdabxvqx.html

find . -mtime -7 -type f
来源：http://dali.zdqjudy.top/Article/details/gtljcaokbq.html

[R45] 批量删除
来源：http://dali.jyoumei.cn/Article/details/gtuptvnsdc.html

find . -name "*.tmp" -delete
来源：http://dali.sxryk.cn/Article/details/gtrrbpipbd.html

[R46] 递归替换文件内容
来源：http://dali.feifeiyinyue.top/Article/details/gtuleuturt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.guannengcc.top/Article/details/gtygqpazrk.html

[R47] sed 单行替换
来源：http://dali.hfpthk.cn/Article/details/gtzkisvohz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtbtsjpobu.html

[R48] awk 取指定列
来源：http://dali.c1oappe.top/Article/details/gtsvaljarz.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj20258.top/Article/details/gtdvltchxu.html

[R49] awk 带条件
来源：http://dali.havefunace.top/Article/details/gtwcdeuxay.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hywenlv.cn/Article/details/gtnxyrtqui.html

[R50] awk 求和
来源：http://dali.bjfxy.top/Article/details/gtlbmlqryj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gthvdsrhdg.html

[R51] 排序去重取前几
来源：http://dali.aizwys.cn/Article/details/gtidfayzlb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xziqi.cn/Article/details/gtkwwpqvqe.html

[R52] 统计行数
来源：http://dali.nanxinkj.top/Article/details/gtviwocehm.html

wc -l a.txt
来源：http://dali.jiagoushi.top/Article/details/gtnhyumzie.html

[R53] 查看文件头与实时尾
来源：http://dali.aibaodan.cn/Article/details/gtjpsltswi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqgulcud.html

[R54] 比较两个文件
来源：http://dali.xylfe.cn/Article/details/gtrnzsalcx.html

diff a.txt b.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtzydepcko.html

[R55] 压缩与解压
来源：http://dali.hongshengwenyu.top/Article/details/gtburyigfa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxuanxn.top/Article/details/gtepnvwlic.html

[R56] 远程拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gteidwtykt.html

scp file user@host:/path/
来源：http://dali.xinyue.icu/Article/details/gtuzjhlxne.html

[R57] 远程执行命令
来源：http://dali.cdnleiting.top/Article/details/gtynzoasbt.html

ssh user@host 'uptime'
来源：http://dali.kuanghao11.cn/Article/details/gtyfvhuqjo.html

[R58] 下载文件
来源：http://dali.316326.xyz/Article/details/gttmdktbfm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.smart0.xyz/Article/details/gtgneujwmq.html

[R59] 发 POST JSON
来源：http://dali.havefunace.top/Article/details/gthvytimgy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yongpay.top/Article/details/gtficmeqgd.html

[R60] 只看 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gtcxpabiea.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhixingplan.top/Article/details/gtrueykghh.html

[R61] 磁盘占用
来源：http://dali.fzhhl.top/Article/details/gtiypdnsxg.html

df -h;  du -sh *
来源：http://dali.nwbrower.top/Article/details/gtckxlifyt.html

[R62] 找最占空间的文件
来源：http://dali.yj20258888.top/Article/details/gtcymkdsmg.html

du -ah . | sort -rh | head -10
来源：http://dali.feifeiyinyue.top/Article/details/gtlwrvupvp.html

[R63] 内存与进程
来源：http://dali.yanxiufei.cn/Article/details/gtskvpropt.html

free -h;  ps aux | grep nginx
来源：http://dali.quarkkingdee.top/Article/details/gtpymfkmaf.html

[R64] 结束进程
来源：http://dali.sxryk.cn/Article/details/gtloyicnai.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj202588.top/Article/details/gtdccnahzs.html

[R65] 查看端口占用
来源：http://dali.9152youxi.cn/Article/details/gtfvfmhbpk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvqrkncs.html

[R66] 定时任务
来源：http://dali.haohaochexian.top/Article/details/gtnvemvqad.html

crontab -e;  crontab -l
来源：http://dali.cucudq.cn/Article/details/gtxldiqbqp.html

[R67] 生成随机十六进制串
来源：http://dali.tianlin.xyz/Article/details/gtsnxyejmm.html

openssl rand -hex 16
来源：http://dali.yonumen.top/Article/details/gtarpkmclf.html

[R68] 计算文件校验值
来源：http://dali.shanyushiyangtech.top/Article/details/gtmfbprxfc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.snrcjt.cn/Article/details/gtfwtrnebv.html

[R69] 生成随机密码
来源：http://dali.yuxming.cn/Article/details/gtfhwxvjro.html

head -c 16 /dev/urandom | base64
来源：http://dali.dashuyun.cn/Article/details/gtnuxzrbin.html

[R70] 时间戳与互转
来源：http://dali.yuanzhike.top/Article/details/gtnpokifvx.html

date +%s;  date -d @1700000000
来源：http://dali.hfpthk.cn/Article/details/gtzsssposd.html

[R71] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gtorsmimnz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ybcxt.top/Article/details/gtcgvzxdbw.html

[R72] 等待端口就绪
来源：http://dali.yangfankeji.com/Article/details/gtdjkjvoex.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gtdstcdfik.html

[R73] 分割大日志
来源：http://dali.andypj.xyz/Article/details/gtfjlyaqji.html

split -l 1000 big.log part_
来源：http://dali.birdmap.top/Article/details/gtyvoetiql.html

[R74] 批量重命名
来源：http://dali.chenlongwang.top/Article/details/gttlznsgwg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.daxiang520.top/Article/details/gtkbbxhnzd.html

[R75] 导出环境变量
来源：http://dali.quarkkingdee.top/Article/details/gtiimtjyep.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenzaomai.com/Article/details/gttfajgnic.html

[R76] 使用临时文件
来源：http://dali.birdmap.top/Article/details/gtpizhdrld.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gtzmlplzum.html

[R77] 读取用户输入
来源：http://dali.gaohongyu789.top/Article/details/gttxdpcupp.html

read -rp "请输入: " ans
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrjrfaobl.html

[R78] 交互式菜单
来源：http://dali.shzxlz.cn/Article/details/gtmglnjiwg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqyvucfb.html

[R79] 解析命令行选项
来源：http://dali.zdqjudy.top/Article/details/gtqnzpnaaj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdgzjwfb.html

[R80] 查看脚本执行耗时
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjppindz.html

time ./run.sh
来源：http://dali.yj202588.top/Article/details/gtvkknojbu.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtrkqyhkzc.html

S. C / C++ 专题
来源：http://dali.c1oappe.top/Article/details/gtecwacpqz.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtbrobbxss.html

[S01] C：Hello World
来源：http://dali.meibo888.top/Article/details/gtyosacdje.html

#include <stdio.h>
来源：http://dali.hnqzz.top/Article/details/gtembsdupw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sufxvd.cn/Article/details/gtouhtsfpx.html

[S02] C：变量与格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gtedxbqpiz.html

int a = 10; printf("%d\n", a);
来源：http://dali.shuidangran.top/Article/details/gtswkdkdwd.html

[S03] C：读入整数
来源：http://dali.gogol.net.cn/Article/details/gtnpoqkrtd.html

int x; scanf("%d", &x);
来源：http://dali.xziqi.cn/Article/details/gttdjdcqim.html

[S04] C：字符串复制
来源：http://dali.zhoulong.xyz/Article/details/gtzzweiskn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuanzx.com/Article/details/gtqkxzkjqc.html

[S05] C：字符串长度
来源：http://dali.zhengqikj.top/Article/details/gtrbnsadsb.html

strlen(s)
来源：http://dali.shzxlz.cn/Article/details/gtohtqxlkv.html

[S06] C：字符串比较
来源：http://dali.yuxming.cn/Article/details/gtgaooaoge.html

strcmp(a, b) == 0
来源：http://dali.jiagoushi.top/Article/details/gtpihhlgud.html

[S07] C：数组遍历求和
来源：http://dali.hfpthk.cn/Article/details/gtfrbaswbw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shzxlz.cn/Article/details/gtcdvktutq.html

[S08] C：动态内存分配与释放
来源：http://dali.gotoacloud.top/Article/details/gtczohojii.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnxiangtu.top/Article/details/gtzysqbrdz.html

[S09] C：结构体定义与初始化
来源：http://dali.ppjwa.cn/Article/details/gtaxpksqrl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cdnleiting.top/Article/details/gtgaxfmwvn.html

[S10] C：指针与解引用
来源：http://dali.316326.xyz/Article/details/gtsifeiicf.html

int *p = &a;  *p = 5;
来源：http://dali.guannengcc.top/Article/details/gtrjcriwkc.html

[S11] C：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjocjebo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.smart0.xyz/Article/details/gtucatknjw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tian-w.cn/Article/details/gthxkeebzt.html

fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcjshjrf.html

[S12] C：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gtdpltongx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sweek.top/Article/details/gtjftqnnih.html

[S13] C：宏定义
来源：http://dali.haohaochexian.top/Article/details/gtpwvzriyx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.fengsongda.top/Article/details/gtpzlbqnhn.html

[S14] C：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtrsjvutfz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shuidangran.top/Article/details/gtwovonlbb.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gtzpymiynx.html

(double) a / b
来源：http://dali.kuanghao11.cn/Article/details/gtwmqpzvlm.html

[S16] C：位操作置位
来源：http://dali.hongshengwenyu.top/Article/details/gtjyfdpnty.html

x |= (1 << 3);
来源：http://dali.nanxuanxn.top/Article/details/gtfyzmtkwo.html

[S17] C：安全拼接字符串
来源：http://dali.bjfxy.top/Article/details/gtnibetjai.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yueranfly.top/Article/details/gtaehkdomx.html

[S18] C：命令行参数
来源：http://dali.guowangkeji.top/Article/details/gtqijatvyn.html

int main(int argc, char **argv)
来源：http://dali.chenzaomai.com/Article/details/gtkmumszoo.html

[S19] C：快速排序
来源：http://dali.yanxiufei.cn/Article/details/gtxujutins.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gtkeaxjbuq.html

[S20] C：二分查找
来源：http://dali.mhx1999.top/Article/details/gtrxrpsakh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gtbmwcvqui.html

[S21] C：字符类别判断
来源：http://dali.jyoumei.cn/Article/details/gtdblweoge.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hywenlv.cn/Article/details/gtjiabfxdq.html

[S22] C：字符串转数字
来源：http://dali.sysykeji.top/Article/details/gtxvvndltg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.andypj.xyz/Article/details/gtnkxhduyz.html

[S23] C：随机数
来源：http://dali.yanxiufei.cn/Article/details/gtjukubjip.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj202588.top/Article/details/gtxxqlouof.html

[S24] C：获取本地时间
来源：http://dali.pycfn.com/Article/details/gtnlifuefk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zycfv.cn/Article/details/gtmkfcgxvi.html

[S25] C：内存拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gtqmvakpxj.html

memcpy(dst, src, n);
来源：http://dali.hfpthk.cn/Article/details/gtwuhdqkrk.html

[S26] C：内存清零
来源：http://dali.meibo888.top/Article/details/gtogzbsode.html

memset(a, 0, sizeof a);
来源：http://dali.yj202588.top/Article/details/gtaolwrlrc.html

[S27] C：定义常量
来源：http://dali.yonumen.top/Article/details/gttbnlvjkt.html

const double PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtufeogrsr.html

[S28] C：静态变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjboualw.html

static int counter = 0;
来源：http://dali.shangyingyoupin.top/Article/details/gtntyoozel.html

[S29] C：变参函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsriqedc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nwbrower.top/Article/details/gtatxwucvu.html

[S30] C：头文件保护
来源：http://dali.shangyingyoupin.top/Article/details/gtheztzsip.html

#ifndef X_H
来源：http://dali.iojbl.cn/Article/details/gtnyshdehl.html

#define X_H
来源：http://dali.daxiang520.top/Article/details/gtncbexnlp.html

#endif
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnngafozj.html

[S31] C++：Hello World
来源：http://dali.fengsongda.top/Article/details/gtawfinhwr.html

#include <iostream>
来源：http://dali.daxiang520.top/Article/details/gtucbfmyhe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.fzhhl.top/Article/details/gttxxsjvga.html

[S32] C++：字符串
来源：http://dali.zhongyouzk.top/Article/details/gttviukqtd.html

std::string s = "hi";  s += "!";
来源：http://dali.ppjwa.cn/Article/details/gtjsnlquhv.html

[S33] C++：vector 增删
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxqhnnvz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.dianchejie.cn/Article/details/gtlwsqdbpa.html

[S34] C++：遍历 vector
来源：http://dali.tanke756.top/Article/details/gtjademmgs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yueranfly.top/Article/details/gtxaitidua.html

[S35] C++：map
来源：http://dali.daria6918.cn/Article/details/gtibyxleaa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtabopopso.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gtpfnqjvib.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtiolzoxyz.html

[S37] C++：set
来源：http://dali.jyoumei.cn/Article/details/gtoguwkhvv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cucudq.cn/Article/details/gteszkqzso.html

[S38] C++：排序
来源：http://dali.ppjwa.cn/Article/details/gtpwkvuwrl.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigufen.top/Article/details/gtceetbxbd.html

[S39] C++：自定义比较器排序
来源：http://dali.snrcjt.cn/Article/details/gtzwhupqai.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.0kj1m.cn/Article/details/gtlgsjbbvn.html

[S40] C++：查找元素
来源：http://dali.yj20258888.top/Article/details/gtmkcyebig.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinqigfzy.top/Article/details/gtskwhczdd.html

[S41] C++：类与构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtuanlbczw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.quarkkingdee.top/Article/details/gtqakrlnbt.html

[S42] C++：继承与虚函数
来源：http://dali.birdmap.top/Article/details/gtdnxlnycg.html

class B : public Base { public: void f() override {} };
来源：http://dali.hongshengwenyu.top/Article/details/gtbvbylkxo.html

[S43] C++：智能指针
来源：http://dali.hongshengwenyu.top/Article/details/gtgdrqzsaz.html

auto p = std::make_unique<int>(5);
来源：http://dali.shzxlz.cn/Article/details/gtrrguwyyy.html

[S44] C++：引用传参
来源：http://dali.tian-w.cn/Article/details/gtfwyoymef.html

void inc(int &x) { ++x; }
来源：http://dali.tanke756.top/Article/details/gtnmotuzfr.html

[S45] C++：lambda
来源：http://dali.jinqigufen.top/Article/details/gtjiyjussl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jlsjyb.cn/Article/details/gtoadeoece.html

[S46] C++：函数模板
来源：http://dali.yj20258.top/Article/details/gtsuxhwkzp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ehwqpu.com/Article/details/gtdfriecgm.html

[S47] C++：结构化绑定遍历
来源：http://dali.pycfn.com/Article/details/gtdpnomekx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258.top/Article/details/gtsnjbrcja.html

[S48] C++：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtnjiytpyy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cdnleiting.top/Article/details/gtwgdmwdfs.html

while (std::getline(in, line)) { }
来源：http://dali.tian-w.cn/Article/details/gtbcbktkis.html

[S49] C++：写文件
来源：http://dali.ydzc1.top/Article/details/gtexqazcej.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cucudq.cn/Article/details/gtjakywdau.html

[S50] C++：格式化数字
来源：http://dali.pengpengdd.cyou/Article/details/gtwvmhxelu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtswszenvp.html

[S51] C++：显式类型转换
来源：http://dali.yuanzhike.top/Article/details/gtxftfwbfw.html

static_cast<double>(a) / b
来源：http://dali.ybcxt.top/Article/details/gtrdblxska.html

[S52] C++：const 与 noexcept
来源：http://dali.chenzaomai.com/Article/details/gtjzcpjzsu.html

int size() const noexcept { return n_; }
来源：http://dali.havefunace.top/Article/details/gtohlhnxml.html

[S53] C++：移动语义
来源：http://dali.xuetiantiany.cn/Article/details/gtjnybwucs.html

std::vector<int> w = std::move(v);
来源：http://dali.yongpay.top/Article/details/gtbbdsmsfo.html

[S54] C++：异常处理
来源：http://dali.ydzc1.top/Article/details/gtcjsgydvl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fzhhl.top/Article/details/gtmaozzryp.html

[S55] C++：结构化绑定
来源：http://dali.yuxming.cn/Article/details/gtvofahlmp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hysaishi.cn/Article/details/gtlmsozorb.html

[S56] C++：optional
来源：http://dali.andypj.xyz/Article/details/gtsmxjwqwe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnxiangtu.top/Article/details/gtdbhidnau.html

[S57] C++：编译期常量
来源：http://dali.iojbl.cn/Article/details/gticnumxgl.html

constexpr int N = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtbvbslkaf.html

[S58] C++：命名空间
来源：http://dali.chenzaomai.com/Article/details/gtxegiioxq.html

namespace ns { int f() { return 1; } }
来源：http://dali.yvedp.cn/Article/details/gtvmrevkwt.html

[S59] C++：静态断言
来源：http://dali.zhixingplan.top/Article/details/gteykgfaiu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangshuangyany.cn/Article/details/gtmqkippcb.html

[S60] C++：遍历并删除元素
来源：http://dali.jianghu66.top/Article/details/gtcmqtoqyx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuxming.cn/Article/details/gtvopynpog.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtateozljl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhoulong.xyz/Article/details/gtxwekhgap.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtzyzenvlj.html

[T01] Kotlin：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gthwqybtba.html

println("Hello")
来源：http://dali.yueranfly.top/Article/details/gtubdxxgkj.html

[T02] Kotlin：变量
来源：http://dali.jinqigfzy.top/Article/details/gttqacjimr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.havefunace.top/Article/details/gtbmxldgig.html

[T03] Kotlin：字符串模板
来源：http://dali.yonumen.top/Article/details/gtmnohlkpa.html

"值: $b"
来源：http://dali.wangshuangyany.cn/Article/details/gtsbefuvpt.html

[T04] Kotlin：空安全
来源：http://dali.quarkkingdee.top/Article/details/gtvyskpsjv.html

val n: String? = null;  n?.length
来源：http://dali.jinqigfzy.top/Article/details/gtyxbbecwf.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258.top/Article/details/gtethcmolg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yangfankeji.com/Article/details/gthvlvhyzl.html

[T06] Kotlin：集合映射
来源：http://dali.sysykeji.top/Article/details/gtdswrbeut.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.aizwys.cn/Article/details/gtgtgcpiri.html

[T07] Kotlin：集合过滤
来源：http://dali.nwbrower.top/Article/details/gttrlotjlf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nwbrower.top/Article/details/gtyasgmmvi.html

[T08] Kotlin：数据类
来源：http://dali.zdqjudy.top/Article/details/gtpkxtiifp.html

data class User(val name: String, val age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gtcobfpbwf.html

[T09] Kotlin：扩展函数
来源：http://dali.ehwqpu.com/Article/details/gtvhprblki.html

fun String.exclaim() = this + "!"
来源：http://dali.yangfankeji.com/Article/details/gtpsusmuwf.html

[T10] Kotlin：默认参数
来源：http://dali.meibo888.top/Article/details/gtwkoujjmc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jiagoushi.top/Article/details/gtffwqysoc.html

[T11] Kotlin：协程
来源：http://dali.yj20258.top/Article/details/gtcuqfvubc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.aizwys.cn/Article/details/gtlnqoujek.html

[T12] Kotlin：解构声明
来源：http://dali.xziqi.cn/Article/details/gtsikoujoh.html

val (a, b) = Pair(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtappnzmix.html

[T13] Kotlin：只读 Map
来源：http://dali.hfpthk.cn/Article/details/gtewigxxeg.html

val m = mapOf("a" to 1)
来源：http://dali.hnxiangtu.top/Article/details/gtxzzanwrc.html

[T14] Kotlin：循环
来源：http://dali.9152youxi.cn/Article/details/gtokvsbmmc.html

for (i in 1..10) println(i)
来源：http://dali.guannengcc.top/Article/details/gtcufrwgls.html

[T15] Kotlin：接口
来源：http://dali.hongshengwenyu.top/Article/details/gtgqehkzoa.html

interface Shape { fun area(): Double }
来源：http://dali.aizwys.cn/Article/details/gtaxzbssig.html

[T16] Swift：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtcdjgqkck.html

print("Hello")
来源：http://dali.daxiang520.top/Article/details/gtkjfrfuet.html


<!-- 参考信息 -->