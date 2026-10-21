代发 wailian999

case "$1" in
来源：http://dali.iojbl.cn/Article/details/gtxodkactm.html

start) echo "启动" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtmddhbkdu.html

stop)  echo "停止" ;;
来源：http://dali.yj20258.top/Article/details/gtxvuebsjk.html

*)     echo "未知命令" ;;
来源：http://dali.yj20258.top/Article/details/gtxftekzfj.html

esac
来源：http://dali.pycfn.com/Article/details/gtyurvdmet.html

[R12] for 遍历文件
来源：http://dali.gaohongyu789.top/Article/details/gtuvyzityn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yongpay.top/Article/details/gtzaxyphyp.html

[R13] for 计数循环
来源：http://dali.svipenyu.cn/Article/details/gtirrpbzbr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.snrcjt.cn/Article/details/gtqxjagyyz.html

[R14] C 风格 for
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjnzrdtdi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnqzz.top/Article/details/gtqbmijzyw.html

[R15] while 逐行读文件
来源：http://dali.sxryk.cn/Article/details/gttbikejxv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhzpljgp.html

[R16] until 等待条件
来源：http://dali.dianchejie.cn/Article/details/gtbuetptxs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gtndabvzgl.html

[R17] 数组定义与取值
来源：http://dali.ehwqpu.com/Article/details/gtfavtgcec.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yuanzhike.top/Article/details/gtbgbtnxlw.html

[R18] 遍历数组
来源：http://dali.yongpay.top/Article/details/gtqarvduji.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jlsjyb.cn/Article/details/gtjuzzxvvl.html

[R19] 数组长度
来源：http://dali.c1oappe.top/Article/details/gtsxdmteet.html

echo "${#arr[@]}"
来源：http://dali.shzxlz.cn/Article/details/gtiuimewhr.html

[R20] 关联数组（字典）
来源：http://dali.hnxiangtu.top/Article/details/gtiwyzgnjl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jlsjyb.cn/Article/details/gtragdthrq.html

[R21] 字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gtrcpaebdq.html

echo "${#s}"
来源：http://dali.nwbrower.top/Article/details/gtpjwismtd.html

[R22] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gtachmbkgo.html

echo "${s:0:5}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgehqtge.html

[R23] 字符串替换
来源：http://dali.tanke756.top/Article/details/gtfczgeori.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhixingplan.top/Article/details/gtiwdhezmn.html

[R24] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gtvibsykai.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.mhx1999.top/Article/details/gtqifgtzcz.html

[R25] 去后缀 / 去前缀
来源：http://dali.ppjwa.cn/Article/details/gtzsakklvd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aizwys.cn/Article/details/gtddyzcoeu.html

[R26] 命令替换
来源：http://dali.cdnleiting.top/Article/details/gtjjwlxmkv.html

now=$(date +%F); echo "$now"
来源：http://dali.mhx1999.top/Article/details/gtnlvfbojp.html

[R27] 算术展开
来源：http://dali.gogol.net.cn/Article/details/gterydanls.html

echo $((1 + 2 * 3))
来源：http://dali.cucudq.cn/Article/details/gtceqhsytq.html

[R28] 浮点运算
来源：http://dali.ehwqpu.com/Article/details/gtxtaxcnyn.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj20258888.top/Article/details/gtmjbqavpr.html

[R29] 定义函数
来源：http://dali.hammf.cn/Article/details/gtcrqiiroe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sxryk.cn/Article/details/gtrqpilplw.html

[R30] 函数返回状态码
来源：http://dali.zhoulong.xyz/Article/details/gtheowqude.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxuanxn.top/Article/details/gthwghboap.html

[R31] 局部变量
来源：http://dali.zhoulong.xyz/Article/details/gtueaqdrgy.html

f() { local x=1; echo "$x"; }
来源：http://dali.yueranfly.top/Article/details/gtnfupnqdw.html

[R32] 参数个数校验
来源：http://dali.sweek.top/Article/details/gtnbofbbxm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gtqoetdwac.html

[R33] 捕获错误并提示行号
来源：http://dali.meibo888.top/Article/details/gtaoslzjgi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnqzz.top/Article/details/gtpfuqdfue.html

[R34] 退出时清理
来源：http://dali.aizwys.cn/Article/details/gtjyimylmg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gtpxerjggs.html

[R35] 后台执行并等待
来源：http://dali.redwolf501.top/Article/details/gtmimigjxb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ehwqpu.com/Article/details/gtmacbwebu.html

[R36] 并发执行多个任务
来源：http://dali.wangshuangyany.cn/Article/details/gtxjepoekj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yangfankeji.com/Article/details/gtuhznoixk.html

[R37] 把输出赋给变量
来源：http://dali.zhongyouzk.top/Article/details/gtqmudrvlg.html

files=$(ls -1)
来源：http://dali.cdnleiting.top/Article/details/gtnqgxqzpd.html

[R38] 管道串联
来源：http://dali.vqdsnc.cn/Article/details/gtavmuhfuc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.mhx1999.top/Article/details/gthrkwgrsf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gtiojqxqoq.html

cmd > out.log 2>&1
来源：http://dali.yj202588.top/Article/details/gtxikcxyvo.html

[R40] 追加写日志
来源：http://dali.sxryk.cn/Article/details/gtziahpehp.html

echo "log" >> out.log
来源：http://dali.guannengcc.top/Article/details/gtjcbuankx.html

[R41] 丢弃输出
来源：http://dali.shangyingyoupin.top/Article/details/gtlezbhujy.html

cmd >/dev/null 2>&1
来源：http://dali.hfpthk.cn/Article/details/gtdyxxuctn.html

[R42] 输入重定向
来源：http://dali.haohaochexian.top/Article/details/gtvhmidkyw.html

wc -l < a.txt
来源：http://dali.ybcxt.top/Article/details/gtajfeyoys.html

[R43] 按名字查找文件
来源：http://dali.sweek.top/Article/details/gtsqwmedrx.html

find . -name "*.log" -type f
来源：http://dali.smart0.xyz/Article/details/gtrzpmpwpe.html

[R44] 按修改时间查找
来源：http://dali.guannengcc.top/Article/details/gtascototc.html

find . -mtime -7 -type f
来源：http://dali.pengpengdd.cyou/Article/details/gtkgmuldqp.html

[R45] 批量删除
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnjcbwvc.html

find . -name "*.tmp" -delete
来源：http://dali.ppjwa.cn/Article/details/gthckudynp.html

[R46] 递归替换文件内容
来源：http://dali.yj20258.top/Article/details/gtbgwagmkr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jiagoushi.top/Article/details/gtfevckjlw.html

[R47] sed 单行替换
来源：http://dali.pycfn.com/Article/details/gtiejmqgwp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hfpthk.cn/Article/details/gtjfjjbdjh.html

[R48] awk 取指定列
来源：http://dali.sufxvd.cn/Article/details/gtychbczig.html

awk '{print $1, $3}' a.txt
来源：http://dali.yvedp.cn/Article/details/gtxpujaoch.html

[R49] awk 带条件
来源：http://dali.zhixingplan.top/Article/details/gteijpzlbw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aizwys.cn/Article/details/gtnyomlbkw.html

[R50] awk 求和
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjbtvstp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtmjsvmfoq.html

[R51] 排序去重取前几
来源：http://dali.jyoumei.cn/Article/details/gtyjdlapwn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fzhhl.top/Article/details/gtwmrmjjfw.html

[R52] 统计行数
来源：http://dali.jianghu66.top/Article/details/gtixgdgnce.html

wc -l a.txt
来源：http://dali.ppjwa.cn/Article/details/gtzsmxnssh.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigfzy.top/Article/details/gtdcrytlxf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ehwqpu.com/Article/details/gtbdpywhsa.html

[R54] 比较两个文件
来源：http://dali.sweek.top/Article/details/gthvkdjumz.html

diff a.txt b.txt
来源：http://dali.wangdashe.top/Article/details/gtdaxbiwpx.html

[R55] 压缩与解压
来源：http://dali.daria6918.cn/Article/details/gtwpbbcwkt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cucudq.cn/Article/details/gtnkjnhjrf.html

[R56] 远程拷贝
来源：http://dali.pycfn.com/Article/details/gtmloiszwp.html

scp file user@host:/path/
来源：http://dali.dianchejie.cn/Article/details/gtecrmkrrt.html

[R57] 远程执行命令
来源：http://dali.hnxiangtu.top/Article/details/gtbpfzbusu.html

ssh user@host 'uptime'
来源：http://dali.dashuyun.cn/Article/details/gtfoqvvuln.html

[R58] 下载文件
来源：http://dali.fengsongda.top/Article/details/gtlgyzowyz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gotoacloud.top/Article/details/gtjzqaehue.html

[R59] 发 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gtunagckoa.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shzxlz.cn/Article/details/gttcivosrf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gtjmckmbwp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jiagoushi.top/Article/details/gtnsffqaif.html

[R61] 磁盘占用
来源：http://dali.hnqzz.top/Article/details/gtyxovfnhx.html

df -h;  du -sh *
来源：http://dali.yj202588.top/Article/details/gtftcsqcow.html

[R62] 找最占空间的文件
来源：http://dali.xuetiantiany.cn/Article/details/gtublvufvv.html

du -ah . | sort -rh | head -10
来源：http://dali.ppjwa.cn/Article/details/gtheuopyda.html

[R63] 内存与进程
来源：http://dali.zhengqikj.top/Article/details/gtxbtnpkgd.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigfzy.top/Article/details/gtjyslyzdj.html

[R64] 结束进程
来源：http://dali.svipenyu.cn/Article/details/gtdymasqtn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuetiantiany.cn/Article/details/gtnwirodkc.html

[R65] 查看端口占用
来源：http://dali.wangshuangyany.cn/Article/details/gtmydaesuc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.daria6918.cn/Article/details/gtalsupeby.html

[R66] 定时任务
来源：http://dali.hysaishi.cn/Article/details/gtgveogchz.html

crontab -e;  crontab -l
来源：http://dali.316326.xyz/Article/details/gtgqtgwibd.html

[R67] 生成随机十六进制串
来源：http://dali.nanxuanxn.top/Article/details/gtbenljmzj.html

openssl rand -hex 16
来源：http://dali.shzxlz.cn/Article/details/gtuolhjois.html

[R68] 计算文件校验值
来源：http://dali.aibaodan.cn/Article/details/gtaxgpskwa.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhixingplan.top/Article/details/gtxhdhfvtp.html

[R69] 生成随机密码
来源：http://dali.meibo888.top/Article/details/gtscoqamvu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhixingplan.top/Article/details/gtleynehfb.html

[R70] 时间戳与互转
来源：http://dali.jiagoushi.top/Article/details/gtfejvrlwh.html

date +%s;  date -d @1700000000
来源：http://dali.cheryme.top/Article/details/gtrkjqwxvj.html

[R71] 日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbupljmi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ehwqpu.com/Article/details/gthjwrbcnw.html

[R72] 等待端口就绪
来源：http://dali.shangyingyoupin.top/Article/details/gtxdrpovfq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gtycoihplw.html

[R73] 分割大日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtslenitcm.html

split -l 1000 big.log part_
来源：http://dali.chenjidiqi.icu/Article/details/gtwftqeqmv.html

[R74] 批量重命名
来源：http://dali.zhoulong.xyz/Article/details/gtppxznpze.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxuanxn.top/Article/details/gtmripssgv.html

[R75] 导出环境变量
来源：http://dali.sweek.top/Article/details/gtiyfnpabs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.bjfxy.top/Article/details/gtuolipsnx.html

[R76] 使用临时文件
来源：http://dali.zhengqikj.top/Article/details/gthkymzovz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangdashe.top/Article/details/gttfrnipsg.html

[R77] 读取用户输入
来源：http://dali.pycfn.com/Article/details/gtucwrpmnh.html

read -rp "请输入: " ans
来源：http://dali.sufxvd.cn/Article/details/gtkwskgrkn.html

[R78] 交互式菜单
来源：http://dali.aibaodan.cn/Article/details/gtpxpbkqtg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.andypj.xyz/Article/details/gtqdmhghww.html

[R79] 解析命令行选项
来源：http://dali.daria6918.cn/Article/details/gtrztbbrbu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgufenzy.top/Article/details/gtciclppwc.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258888.top/Article/details/gtenixksdv.html

time ./run.sh
来源：http://dali.hammf.cn/Article/details/gtbxipetls.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvmbvwlg.html

S. C / C++ 专题
来源：http://dali.smart0.xyz/Article/details/gtylzsbfkx.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtvfbkdqhp.html

[S01] C：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtwhtqgejl.html

#include <stdio.h>
来源：http://dali.andypj.xyz/Article/details/gtfizorrmo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.smart0.xyz/Article/details/gtvwqpcref.html

[S02] C：变量与格式化输出
来源：http://dali.guowangkeji.top/Article/details/gtcdahpwfj.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgufenzy.top/Article/details/gtbfsauzpj.html

[S03] C：读入整数
来源：http://dali.xuanzx.com/Article/details/gtwkhgcsyq.html

int x; scanf("%d", &x);
来源：http://dali.jlsjyb.cn/Article/details/gtzqlwvblz.html

[S04] C：字符串复制
来源：http://dali.bjfxy.top/Article/details/gtdwpdnqfr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.birdmap.top/Article/details/gtdfnouqwk.html

[S05] C：字符串长度
来源：http://dali.yvedp.cn/Article/details/gtdsmutzpa.html

strlen(s)
来源：http://dali.yj20258888.top/Article/details/gthdgiwnpn.html

[S06] C：字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gtwouqhexr.html

strcmp(a, b) == 0
来源：http://dali.mhx1999.top/Article/details/gtgaryynls.html

[S07] C：数组遍历求和
来源：http://dali.zhengqikj.top/Article/details/gtgfgludtq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xinyue.icu/Article/details/gtbspigdwz.html

[S08] C：动态内存分配与释放
来源：http://dali.hywenlv.cn/Article/details/gtouyucuea.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuetiantiany.cn/Article/details/gtfvjqhpam.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258.top/Article/details/gtcpnfknre.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhiwuduotai.top/Article/details/gtvjxvfxym.html

[S10] C：指针与解引用
来源：http://dali.zhiwuduotai.top/Article/details/gtbqxvdjaz.html

int *p = &a;  *p = 5;
来源：http://dali.xylfe.cn/Article/details/gtvvswwvgd.html

[S11] C：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtquethmyz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zycfv.cn/Article/details/gteowaizga.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.9152youxi.cn/Article/details/gtnjadmpuq.html

fclose(f);
来源：http://dali.wangdashe.top/Article/details/gtjmazuhnb.html

[S12] C：写文件
来源：http://dali.ivvv.top/Article/details/gtkbnjxgqu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtyynczpug.html

[S13] C：宏定义
来源：http://dali.hongshengwenyu.top/Article/details/gtdvxmkqwz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdurtqzb.html

[S14] C：枚举
来源：http://dali.gotoacloud.top/Article/details/gtxvplwsfi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jqgufenzy.top/Article/details/gtsbltuokl.html

[S15] C：类型转换
来源：http://dali.ppjwa.cn/Article/details/gtruuclfxr.html

(double) a / b
来源：http://dali.ppjwa.cn/Article/details/gtagbizyug.html

[S16] C：位操作置位
来源：http://dali.zhiwuduotai.top/Article/details/gtplnuihic.html

x |= (1 << 3);
来源：http://dali.9152youxi.cn/Article/details/gtuekcabzl.html

[S17] C：安全拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtssormyey.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xuetiantiany.cn/Article/details/gttjligxei.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvhwdkml.html

int main(int argc, char **argv)
来源：http://dali.pengpengdd.cyou/Article/details/gtqagpkiod.html

[S19] C：快速排序
来源：http://dali.gaohongyu789.top/Article/details/gtzeiqyqos.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtgysrnoau.html

[S20] C：二分查找
来源：http://dali.chenzaomai.com/Article/details/gtlmwllhae.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gttkmdkojo.html

[S21] C：字符类别判断
来源：http://dali.meibo888.top/Article/details/gtwcjxcxjp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhoulong.xyz/Article/details/gtrfzulvdk.html

[S22] C：字符串转数字
来源：http://dali.redwolf501.top/Article/details/gtmoxltnoo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.kuanghao11.cn/Article/details/gtauerggly.html

[S23] C：随机数
来源：http://dali.cdnleiting.top/Article/details/gtkacqtbqs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fengsongda.top/Article/details/gtrcglsykc.html

[S24] C：获取本地时间
来源：http://dali.chenlongwang.top/Article/details/gtsqdezmuz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jqgfzy.top/Article/details/gtimalywvb.html

[S25] C：内存拷贝
来源：http://dali.gogol.net.cn/Article/details/gtkhqnuseo.html

memcpy(dst, src, n);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmvvlzyn.html

[S26] C：内存清零
来源：http://dali.yuanzhike.top/Article/details/gtfzvbxwzf.html

memset(a, 0, sizeof a);
来源：http://dali.havefunace.top/Article/details/gtmwkwfchg.html

[S27] C：定义常量
来源：http://dali.chenjidiqi.icu/Article/details/gtkzwekfjd.html

const double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwszflptl.html

[S28] C：静态变量
来源：http://dali.tianlin.xyz/Article/details/gtxcunxxoq.html

static int counter = 0;
来源：http://dali.sufxvd.cn/Article/details/gtdebqnibn.html

[S29] C：变参函数
来源：http://dali.xylfe.cn/Article/details/gtybghzmxp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cdnleiting.top/Article/details/gtlpclfiii.html

[S30] C：头文件保护
来源：http://dali.guowangkeji.top/Article/details/gtsxinyhvx.html

#ifndef X_H
来源：http://dali.zycfv.cn/Article/details/gttjisvxsf.html

#define X_H
来源：http://dali.yuxming.cn/Article/details/gteachnszk.html

#endif
来源：http://dali.nanxinkj.top/Article/details/gtjidjkvnz.html

[S31] C++：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtqeynlurw.html

#include <iostream>
来源：http://dali.xuetiantiany.cn/Article/details/gthiityzsb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.bjfxy.top/Article/details/gtvoesvxah.html

[S32] C++：字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanozdqzs.html

std::string s = "hi";  s += "!";
来源：http://dali.cashguo.top/Article/details/gtgyfqgdgb.html

[S33] C++：vector 增删
来源：http://dali.havefunace.top/Article/details/gtzovjmhky.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hywenlv.cn/Article/details/gtpsjpatpb.html

[S34] C++：遍历 vector
来源：http://dali.cheryme.top/Article/details/gthrjicyvh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gzhubu.top/Article/details/gtuhbfhacu.html

[S35] C++：map
来源：http://dali.nanxinkj.top/Article/details/gttwrsehok.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtzbazqnvi.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gtczvbrzlv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gtcpdgaeyf.html

[S37] C++：set
来源：http://dali.tanke756.top/Article/details/gtbgphrcsn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.dianchejie.cn/Article/details/gtdthmscjn.html

[S38] C++：排序
来源：http://dali.yueranfly.top/Article/details/gtkykdjofq.html

std::sort(v.begin(), v.end());
来源：http://dali.daria6918.cn/Article/details/gtferheltv.html

[S39] C++：自定义比较器排序
来源：http://dali.ppjwa.cn/Article/details/gtsnlkmtky.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ivvv.top/Article/details/gttzbexncu.html

[S40] C++：查找元素
来源：http://dali.ivvv.top/Article/details/gtnwyqxlkk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gtojphcewk.html

[S41] C++：类与构造函数
来源：http://dali.ehwqpu.com/Article/details/gtuyoiclmn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gogol.net.cn/Article/details/gtokvyxzfs.html

[S42] C++：继承与虚函数
来源：http://dali.shzxlz.cn/Article/details/gtryfhsxsb.html

class B : public Base { public: void f() override {} };
来源：http://dali.jiagoushi.top/Article/details/gtcefphsoj.html

[S43] C++：智能指针
来源：http://dali.meibo888.top/Article/details/gtmgfrlnea.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258888.top/Article/details/gtipafqacd.html

[S44] C++：引用传参
来源：http://dali.tianlin.xyz/Article/details/gtknshquax.html

void inc(int &x) { ++x; }
来源：http://dali.jlsjyb.cn/Article/details/gtkgmwwbmr.html

[S45] C++：lambda
来源：http://dali.ydzc1.top/Article/details/gtwmxorose.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aibaodan.cn/Article/details/gtfqzddote.html

[S46] C++：函数模板
来源：http://dali.andypj.xyz/Article/details/gtusnpmtjt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xylfe.cn/Article/details/gtfjsjsngd.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gtvyehsqti.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnqzz.top/Article/details/gtjvoralqa.html

[S48] C++：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtsejnouzj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258888.top/Article/details/gtbrswggox.html

while (std::getline(in, line)) { }
来源：http://dali.hywenlv.cn/Article/details/gtexeocgjh.html

[S49] C++：写文件
来源：http://dali.cashguo.top/Article/details/gtfnvimwtx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.redwolf501.top/Article/details/gtrnfpfqpu.html

[S50] C++：格式化数字
来源：http://dali.hysaishi.cn/Article/details/gttyjfpvmg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtgmanermj.html

[S51] C++：显式类型转换
来源：http://dali.jyoumei.cn/Article/details/gtuzrzfqwi.html

static_cast<double>(a) / b
来源：http://dali.9152youxi.cn/Article/details/gtlsaqgzcy.html

[S52] C++：const 与 noexcept
来源：http://dali.dashuyun.cn/Article/details/gtneycvyjd.html

int size() const noexcept { return n_; }
来源：http://dali.vqdsnc.cn/Article/details/gtfwtrcbyg.html

[S53] C++：移动语义
来源：http://dali.guannengcc.top/Article/details/gtsecsssbk.html

std::vector<int> w = std::move(v);
来源：http://dali.chenzaomai.com/Article/details/gtpylyiild.html

[S54] C++：异常处理
来源：http://dali.0kj1m.cn/Article/details/gtdrzopuuh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aibaodan.cn/Article/details/gtmdrfidao.html

[S55] C++：结构化绑定
来源：http://dali.hammf.cn/Article/details/gtjhmgwjto.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aizwys.cn/Article/details/gtmavzcgqs.html

[S56] C++：optional
来源：http://dali.xziqi.cn/Article/details/gtedodqmwr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.haohaochexian.top/Article/details/gtdatwbghe.html

[S57] C++：编译期常量
来源：http://dali.gzhubu.top/Article/details/gtgleohjha.html

constexpr int N = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtiyxlnyqs.html

[S58] C++：命名空间
来源：http://dali.aizwys.cn/Article/details/gtqblydwpc.html

namespace ns { int f() { return 1; } }
来源：http://dali.fzhhl.top/Article/details/gtshfqoskw.html

[S59] C++：静态断言
来源：http://dali.cqqwz.cn/Article/details/gtyoymokkq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdvysptog.html

[S60] C++：遍历并删除元素
来源：http://dali.yongpay.top/Article/details/gtwohibbdm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hywenlv.cn/Article/details/gtldwulnoh.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtcmsyeley.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcocnoubd.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtjrvbjdyw.html

[T01] Kotlin：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtpjmjvayd.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtqzbmuxgl.html

[T02] Kotlin：变量
来源：http://dali.tianlin.xyz/Article/details/gtwmrrewaa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangtech.top/Article/details/gtytkomadx.html

[T03] Kotlin：字符串模板
来源：http://dali.xinyue.icu/Article/details/gtzzcyunaw.html

"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwrbhnew.html

[T04] Kotlin：空安全
来源：http://dali.xylfe.cn/Article/details/gtommvcjqs.html

val n: String? = null;  n?.length
来源：http://dali.gotoacloud.top/Article/details/gtwvtnffkq.html

[T05] Kotlin：when 表达式
来源：http://dali.guannengcc.top/Article/details/gtqtfrstgm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shzxlz.cn/Article/details/gtdvrbikmk.html

[T06] Kotlin：集合映射
来源：http://dali.zycfv.cn/Article/details/gtdpswpmlb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.aizwys.cn/Article/details/gtnpaleqfk.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258888.top/Article/details/gtbwqkdxye.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgfzy.top/Article/details/gtmhbcbxoe.html

[T08] Kotlin：数据类
来源：http://dali.hnqzz.top/Article/details/gtjqcrqcio.html

data class User(val name: String, val age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gtgapfpyve.html

[T09] Kotlin：扩展函数
来源：http://dali.andypj.xyz/Article/details/gtkduucccl.html

fun String.exclaim() = this + "!"
来源：http://dali.havefunace.top/Article/details/gtnlisxxto.html

[T10] Kotlin：默认参数
来源：http://dali.bjfxy.top/Article/details/gtomriredz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenlongwang.top/Article/details/gtfqvcleic.html

[T11] Kotlin：协程
来源：http://dali.gogol.net.cn/Article/details/gtnusgyrrs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hongshengwenyu.top/Article/details/gtbpvruzop.html

[T12] Kotlin：解构声明
来源：http://dali.jianghu66.top/Article/details/gtdadiwxeq.html

val (a, b) = Pair(1, 2)
来源：http://dali.gzhubu.top/Article/details/gtmccdderv.html


<!-- 参考信息 -->