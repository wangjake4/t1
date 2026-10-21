代发 wailian999

case "$1" in
来源：http://dali.daria6918.cn/Article/details/gtfxabqkkv.html

start) echo "启动" ;;
来源：http://dali.cdnleiting.top/Article/details/gtkkcugcuu.html

stop)  echo "停止" ;;
来源：http://dali.fzhhl.top/Article/details/gtwedmokku.html

*)     echo "未知命令" ;;
来源：http://dali.xylfe.cn/Article/details/gtuckaisbe.html

esac
来源：http://dali.quarkkingdee.top/Article/details/gtovfsdlro.html

[R12] for 遍历文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gttyvvgfit.html

for f in *.txt; do echo "$f"; done
来源：http://dali.birdmap.top/Article/details/gthaklbyll.html

[R13] for 计数循环
来源：http://dali.shangyingyoupin.top/Article/details/gtpvlchubq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.snrcjt.cn/Article/details/gtsqdzwzgn.html

[R14] C 风格 for
来源：http://dali.kuanghao11.cn/Article/details/gtjcaeuiec.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.andypj.xyz/Article/details/gtdzvjplot.html

[R15] while 逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtseylusfb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ybcxt.top/Article/details/gtsrvmjdei.html

[R16] until 等待条件
来源：http://dali.jqgfzy.top/Article/details/gtolilqbxl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gtlabwzzfy.html

[R17] 数组定义与取值
来源：http://dali.daxiang520.top/Article/details/gtyywnuiow.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ybcxt.top/Article/details/gtbdhbpvjm.html

[R18] 遍历数组
来源：http://dali.ydzc1.top/Article/details/gtiopuhkye.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtuhpvdamr.html

[R19] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gthcxsxmgr.html

echo "${#arr[@]}"
来源：http://dali.andypj.xyz/Article/details/gthvsxlbrj.html

[R20] 关联数组（字典）
来源：http://dali.chenjidiqi.icu/Article/details/gtnwrxwdua.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.andypj.xyz/Article/details/gtuqywzdsz.html

[R21] 字符串长度
来源：http://dali.meibo888.top/Article/details/gttdzmhyvr.html

echo "${#s}"
来源：http://dali.yvedp.cn/Article/details/gtujwpmkax.html

[R22] 截取子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjtixhgw.html

echo "${s:0:5}"
来源：http://dali.iojbl.cn/Article/details/gtnojuydyy.html

[R23] 字符串替换
来源：http://dali.birdmap.top/Article/details/gtyfqusxci.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fzhhl.top/Article/details/gtjrmuhbwx.html

[R24] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gttqonjrtv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yongpay.top/Article/details/gtaoeuneuo.html

[R25] 去后缀 / 去前缀
来源：http://dali.cheryme.top/Article/details/gtcvphfcry.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tanke756.top/Article/details/gtiajvbdoq.html

[R26] 命令替换
来源：http://dali.fengsongda.top/Article/details/gtjvkstzuy.html

now=$(date +%F); echo "$now"
来源：http://dali.andypj.xyz/Article/details/gtydaoqmem.html

[R27] 算术展开
来源：http://dali.yangfankeji.com/Article/details/gtrwnrbfgi.html

echo $((1 + 2 * 3))
来源：http://dali.andypj.xyz/Article/details/gtxyktzgxt.html

[R28] 浮点运算
来源：http://dali.feifeiyinyue.top/Article/details/gtrmlarspu.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenlongwang.top/Article/details/gtbklytkrb.html

[R29] 定义函数
来源：http://dali.0kj1m.cn/Article/details/gtcmoswinx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yongpay.top/Article/details/gtjlrswsew.html

[R30] 函数返回状态码
来源：http://dali.zhoulong.xyz/Article/details/gtlplrexwi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuxming.cn/Article/details/gtkdzpszsl.html

[R31] 局部变量
来源：http://dali.yvedp.cn/Article/details/gtprmwuvxn.html

f() { local x=1; echo "$x"; }
来源：http://dali.mhx1999.top/Article/details/gtnpjnnfjj.html

[R32] 参数个数校验
来源：http://dali.meibo888.top/Article/details/gtiywdfwzp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gtvlrplpoo.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxuanxn.top/Article/details/gtknpdyhny.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yangfankeji.com/Article/details/gtgdysqvyz.html

[R34] 退出时清理
来源：http://dali.yueranfly.top/Article/details/gtksrdclcn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gtancmrstq.html

[R35] 后台执行并等待
来源：http://dali.yvedp.cn/Article/details/gtilndssqi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.birdmap.top/Article/details/gtgerlpihq.html

[R36] 并发执行多个任务
来源：http://dali.yuanzhike.top/Article/details/gthjtyszkr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yvedp.cn/Article/details/gtejademeg.html

[R37] 把输出赋给变量
来源：http://dali.cqqwz.cn/Article/details/gtixxsbvnf.html

files=$(ls -1)
来源：http://dali.chenlongwang.top/Article/details/gtzmtkeabk.html

[R38] 管道串联
来源：http://dali.jinghuilouyu.cn/Article/details/gtmaivvytr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcfxvocex.html

[R39] 重定向标准输出与错误
来源：http://dali.guannengcc.top/Article/details/gtcakutrma.html

cmd > out.log 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gttunmcwvt.html

[R40] 追加写日志
来源：http://dali.zycfv.cn/Article/details/gtxacbueqj.html

echo "log" >> out.log
来源：http://dali.aibaodan.cn/Article/details/gttwvojhdt.html

[R41] 丢弃输出
来源：http://dali.yj20258.top/Article/details/gtpvahpfhn.html

cmd >/dev/null 2>&1
来源：http://dali.hnqzz.top/Article/details/gtndltccri.html

[R42] 输入重定向
来源：http://dali.hfpthk.cn/Article/details/gtrfpzyhkq.html

wc -l < a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtpaypqrqc.html

[R43] 按名字查找文件
来源：http://dali.sxryk.cn/Article/details/gtbsaezuxg.html

find . -name "*.log" -type f
来源：http://dali.jyoumei.cn/Article/details/gtxtgvzhjq.html

[R44] 按修改时间查找
来源：http://dali.zycfv.cn/Article/details/gtpyudzyoh.html

find . -mtime -7 -type f
来源：http://dali.fengsongda.top/Article/details/gtwqwxehra.html

[R45] 批量删除
来源：http://dali.jyoumei.cn/Article/details/gtusqlgdtl.html

find . -name "*.tmp" -delete
来源：http://dali.sweek.top/Article/details/gthfskrpuk.html

[R46] 递归替换文件内容
来源：http://dali.sufxvd.cn/Article/details/gtpslaczzp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cucudq.cn/Article/details/gtsyzcbrjm.html

[R47] sed 单行替换
来源：http://dali.ydzc1.top/Article/details/gtpfgtcldb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yonumen.top/Article/details/gtgfogapmo.html

[R48] awk 取指定列
来源：http://dali.xinyue.icu/Article/details/gtbfftaijc.html

awk '{print $1, $3}' a.txt
来源：http://dali.wangdashe.top/Article/details/gtylmczouq.html

[R49] awk 带条件
来源：http://dali.andypj.xyz/Article/details/gttmuteawm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.guowangkeji.top/Article/details/gtcqtyanqf.html

[R50] awk 求和
来源：http://dali.sxryk.cn/Article/details/gtmyqaaudf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yonumen.top/Article/details/gtjklwyzmu.html

[R51] 排序去重取前几
来源：http://dali.yj20258.top/Article/details/gtvpqofcpn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgufenzy.top/Article/details/gtpurirlrf.html

[R52] 统计行数
来源：http://dali.kuanghao11.cn/Article/details/gtnwthodjv.html

wc -l a.txt
来源：http://dali.sxryk.cn/Article/details/gtfoyerfty.html

[R53] 查看文件头与实时尾
来源：http://dali.yuxming.cn/Article/details/gtdxqsfkuv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guannengcc.top/Article/details/gtxjyjdrmo.html

[R54] 比较两个文件
来源：http://dali.chenlongwang.top/Article/details/gtiipqgmcg.html

diff a.txt b.txt
来源：http://dali.hywenlv.cn/Article/details/gtzzcbtcyq.html

[R55] 压缩与解压
来源：http://dali.vqdsnc.cn/Article/details/gtzgkxzdaa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tian-w.cn/Article/details/gtqyelelpt.html

[R56] 远程拷贝
来源：http://dali.haohaochexian.top/Article/details/gtaidczgbt.html

scp file user@host:/path/
来源：http://dali.zhoulong.xyz/Article/details/gtwzddiauz.html

[R57] 远程执行命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gtscrivwpv.html

ssh user@host 'uptime'
来源：http://dali.xylfe.cn/Article/details/gtajtofpxk.html

[R58] 下载文件
来源：http://dali.xinyue.icu/Article/details/gtyzujjdlp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.kuanghao11.cn/Article/details/gtybxikfxo.html

[R59] 发 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gtdmyrnity.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenzaomai.com/Article/details/gtvnocuods.html

[R60] 只看 HTTP 状态码
来源：http://dali.ydzc1.top/Article/details/gtnhsituot.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sufxvd.cn/Article/details/gtqfhdvini.html

[R61] 磁盘占用
来源：http://dali.yonumen.top/Article/details/gtirmvfyxw.html

df -h;  du -sh *
来源：http://dali.jyoumei.cn/Article/details/gtirwpnypo.html

[R62] 找最占空间的文件
来源：http://dali.yuxming.cn/Article/details/gtgbjdvepm.html

du -ah . | sort -rh | head -10
来源：http://dali.fengsongda.top/Article/details/gtlequpjcx.html

[R63] 内存与进程
来源：http://dali.ivvv.top/Article/details/gtyiephwcx.html

free -h;  ps aux | grep nginx
来源：http://dali.sweek.top/Article/details/gtyphcxpbw.html

[R64] 结束进程
来源：http://dali.smart0.xyz/Article/details/gtjiqhnogi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sweek.top/Article/details/gtoqeuvdix.html

[R65] 查看端口占用
来源：http://dali.yj202588.top/Article/details/gtamfevvxk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhoulong.xyz/Article/details/gtqsskosnr.html

[R66] 定时任务
来源：http://dali.jyoumei.cn/Article/details/gtkwiqchsb.html

crontab -e;  crontab -l
来源：http://dali.yongpay.top/Article/details/gtqsrganof.html

[R67] 生成随机十六进制串
来源：http://dali.xylfe.cn/Article/details/gtyhkqbwjc.html

openssl rand -hex 16
来源：http://dali.tanke756.top/Article/details/gtxyxdxpni.html

[R68] 计算文件校验值
来源：http://dali.cdnleiting.top/Article/details/gtmxlsndqe.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtiicyzlak.html

[R69] 生成随机密码
来源：http://dali.pengpengdd.cyou/Article/details/gtuaxffszn.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj20258.top/Article/details/gtqlbgxuud.html

[R70] 时间戳与互转
来源：http://dali.kuanghao11.cn/Article/details/gtevwjczzz.html

date +%s;  date -d @1700000000
来源：http://dali.yonumen.top/Article/details/gtzpmyndug.html

[R71] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzafcmrd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258888.top/Article/details/gtocgddmin.html

[R72] 等待端口就绪
来源：http://dali.cheryme.top/Article/details/gtrccygqnw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pycfn.com/Article/details/gtfrwudqty.html

[R73] 分割大日志
来源：http://dali.xuanzx.com/Article/details/gtlkbyijrg.html

split -l 1000 big.log part_
来源：http://dali.ppjwa.cn/Article/details/gtfvncwxuf.html

[R74] 批量重命名
来源：http://dali.0kj1m.cn/Article/details/gtjyjwjiqe.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hywenlv.cn/Article/details/gtycvpfhow.html

[R75] 导出环境变量
来源：http://dali.sxryk.cn/Article/details/gtcmszcjvv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sufxvd.cn/Article/details/gtwpeljzzi.html

[R76] 使用临时文件
来源：http://dali.yj202588.top/Article/details/gtdcoyxgew.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gtmzqdkfvm.html

[R77] 读取用户输入
来源：http://dali.hywenlv.cn/Article/details/gtcetfbtdk.html

read -rp "请输入: " ans
来源：http://dali.meibo888.top/Article/details/gtyszpeqvu.html

[R78] 交互式菜单
来源：http://dali.cashguo.top/Article/details/gtmldlvlhu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuanzhike.top/Article/details/gtwzhmysps.html

[R79] 解析命令行选项
来源：http://dali.cashguo.top/Article/details/gtcffabmmh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hammf.cn/Article/details/gtbcpwsapb.html

[R80] 查看脚本执行耗时
来源：http://dali.pycfn.com/Article/details/gtoivqcigv.html

time ./run.sh
来源：http://dali.ivvv.top/Article/details/gteqavobuf.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtffqtcpfg.html

S. C / C++ 专题
来源：http://dali.sweek.top/Article/details/gtskkgimzo.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtsoskodiz.html

[S01] C：Hello World
来源：http://dali.wangdashe.top/Article/details/gthpprmzog.html

#include <stdio.h>
来源：http://dali.dianchejie.cn/Article/details/gtegvkdila.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.havefunace.top/Article/details/gtxvrxtlfq.html

[S02] C：变量与格式化输出
来源：http://dali.fengsongda.top/Article/details/gtbmcjubdf.html

int a = 10; printf("%d\n", a);
来源：http://dali.cashguo.top/Article/details/gtiidoqdyp.html

[S03] C：读入整数
来源：http://dali.bjfxy.top/Article/details/gtyahoomrr.html

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdvozzdw.html

[S04] C：字符串复制
来源：http://dali.yanxiufei.cn/Article/details/gtdjbgodip.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ivvv.top/Article/details/gtcopqslgv.html

[S05] C：字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gtxjswkzzz.html

strlen(s)
来源：http://dali.ehwqpu.com/Article/details/gtfugxuasz.html

[S06] C：字符串比较
来源：http://dali.0kj1m.cn/Article/details/gtuzvpyccd.html

strcmp(a, b) == 0
来源：http://dali.jiagoushi.top/Article/details/gtgecmxtdt.html

[S07] C：数组遍历求和
来源：http://dali.tian-w.cn/Article/details/gtymmsjafb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxuanxn.top/Article/details/gtyzlzqllv.html

[S08] C：动态内存分配与释放
来源：http://dali.hfpthk.cn/Article/details/gtttwjuzfr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenlongwang.top/Article/details/gtfvustuhm.html

[S09] C：结构体定义与初始化
来源：http://dali.9152youxi.cn/Article/details/gtkuypcdla.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cheryme.top/Article/details/gtkrcgqvcz.html

[S10] C：指针与解引用
来源：http://dali.yonumen.top/Article/details/gtrchdbtpp.html

int *p = &a;  *p = 5;
来源：http://dali.tian-w.cn/Article/details/gtfqamocjn.html

[S11] C：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtqrmgzjmb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yvedp.cn/Article/details/gtemlbvmsj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxinkj.top/Article/details/gtjqlewekz.html

fclose(f);
来源：http://dali.daxiang520.top/Article/details/gtmgrrphqh.html

[S12] C：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtysgalcun.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.andypj.xyz/Article/details/gtdrstpzzq.html

[S13] C：宏定义
来源：http://dali.shuidangran.top/Article/details/gtbshxsoaw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.andypj.xyz/Article/details/gtakjipxkb.html

[S14] C：枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtcxgrykld.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfenvkreq.html

[S15] C：类型转换
来源：http://dali.fzhhl.top/Article/details/gthuvdkroe.html

(double) a / b
来源：http://dali.aibaodan.cn/Article/details/gtabdnisgt.html

[S16] C：位操作置位
来源：http://dali.hammf.cn/Article/details/gtusjklzuv.html

x |= (1 << 3);
来源：http://dali.nanxinkj.top/Article/details/gtnrmqmnbo.html

[S17] C：安全拼接字符串
来源：http://dali.zycfv.cn/Article/details/gtobpfutuc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gaohongyu789.top/Article/details/gtslnczldl.html

[S18] C：命令行参数
来源：http://dali.cheryme.top/Article/details/gtdpkaqqki.html

int main(int argc, char **argv)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovvvsghy.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gtddkqvxez.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gtjiyvwdui.html

[S20] C：二分查找
来源：http://dali.hysaishi.cn/Article/details/gtpdyelwqk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gtxdvvohjg.html

[S21] C：字符类别判断
来源：http://dali.bjfxy.top/Article/details/gttvhffdgc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.mhx1999.top/Article/details/gtfciwhiuk.html

[S22] C：字符串转数字
来源：http://dali.guannengcc.top/Article/details/gtacgrtfhs.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ydzc1.top/Article/details/gtujsbvapt.html

[S23] C：随机数
来源：http://dali.andypj.xyz/Article/details/gtckelgwud.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daria6918.cn/Article/details/gtwzpezcnc.html

[S24] C：获取本地时间
来源：http://dali.jqgfzy.top/Article/details/gtzrmvrdaw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258.top/Article/details/gtwttwiytn.html

[S25] C：内存拷贝
来源：http://dali.jiagoushi.top/Article/details/gtktlfofsv.html

memcpy(dst, src, n);
来源：http://dali.zhoulong.xyz/Article/details/gtffyegxfh.html

[S26] C：内存清零
来源：http://dali.havefunace.top/Article/details/gtpiutbckf.html

memset(a, 0, sizeof a);
来源：http://dali.cucudq.cn/Article/details/gtkdxriroj.html

[S27] C：定义常量
来源：http://dali.cucudq.cn/Article/details/gtqrumvfbk.html

const double PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtrzulmenr.html

[S28] C：静态变量
来源：http://dali.zhongyouzk.top/Article/details/gtkkngmefc.html

static int counter = 0;
来源：http://dali.zhixingplan.top/Article/details/gtpdbglpcu.html

[S29] C：变参函数
来源：http://dali.ppjwa.cn/Article/details/gtqdwvbupf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yueranfly.top/Article/details/gttnlnfueq.html

[S30] C：头文件保护
来源：http://dali.daxiang520.top/Article/details/gtlfkvtvkw.html

#ifndef X_H
来源：http://dali.andypj.xyz/Article/details/gthujawvew.html

#define X_H
来源：http://dali.jinqigufen.top/Article/details/gtpvlhjhlx.html

#endif
来源：http://dali.hysaishi.cn/Article/details/gtsjhycszj.html

[S31] C++：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtuzycdjtb.html

#include <iostream>
来源：http://dali.hongshengwenyu.top/Article/details/gtohgnrkgw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqipylmzc.html

[S32] C++：字符串
来源：http://dali.pycfn.com/Article/details/gtnwybxbla.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqxblxig.html

[S33] C++：vector 增删
来源：http://dali.snrcjt.cn/Article/details/gtfcejlldw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yongpay.top/Article/details/gtrukygcxq.html

[S34] C++：遍历 vector
来源：http://dali.mhx1999.top/Article/details/gthfqyicwq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tianlin.xyz/Article/details/gtjvescasg.html

[S35] C++：map
来源：http://dali.wangshuangyany.cn/Article/details/gtjjghguti.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqfasaau.html

[S36] C++：unordered_map
来源：http://dali.yvedp.cn/Article/details/gtzipwdyir.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gtcumhhqoi.html

[S37] C++：set
来源：http://dali.gzhubu.top/Article/details/gtdoqzjxvg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtgoyualiv.html

[S38] C++：排序
来源：http://dali.jinqigfzy.top/Article/details/gtoprsuoig.html

std::sort(v.begin(), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpenezgs.html

[S39] C++：自定义比较器排序
来源：http://dali.hongshengwenyu.top/Article/details/gtxtpdvteh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupalxhsz.html

[S40] C++：查找元素
来源：http://dali.meibo888.top/Article/details/gtoxgztprb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtumbeiexy.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtlgiteeqe.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jiagoushi.top/Article/details/gtlrccogaa.html

[S42] C++：继承与虚函数
来源：http://dali.chenzaomai.com/Article/details/gtmlildzzk.html

class B : public Base { public: void f() override {} };
来源：http://dali.xinyue.icu/Article/details/gtknmawojs.html

[S43] C++：智能指针
来源：http://dali.tanke756.top/Article/details/gtkbphdtou.html

auto p = std::make_unique<int>(5);
来源：http://dali.daria6918.cn/Article/details/gtafhzqbmr.html

[S44] C++：引用传参
来源：http://dali.tian-w.cn/Article/details/gtoqfmoyyo.html

void inc(int &x) { ++x; }
来源：http://dali.hfpthk.cn/Article/details/gtzvgizunx.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gtddrhglmk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fengsongda.top/Article/details/gtliagcohj.html

[S46] C++：函数模板
来源：http://dali.tian-w.cn/Article/details/gtdbhyabjz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.316326.xyz/Article/details/gtrhyqnnhc.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvqrmscb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sysykeji.top/Article/details/gtpotdcqsk.html

[S48] C++：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtbtkrbkbo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cdnleiting.top/Article/details/gtobeporxk.html

while (std::getline(in, line)) { }
来源：http://dali.andypj.xyz/Article/details/gtlbfekmiz.html

[S49] C++：写文件
来源：http://dali.meibo888.top/Article/details/gtsjeobdze.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yvedp.cn/Article/details/gtlbyjhkqv.html

[S50] C++：格式化数字
来源：http://dali.yanxiufei.cn/Article/details/gtzqjrmdla.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtlsdzuswk.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gttcfuhiyl.html

static_cast<double>(a) / b
来源：http://dali.wangshuangyany.cn/Article/details/gtblfrrixt.html

[S52] C++：const 与 noexcept
来源：http://dali.iojbl.cn/Article/details/gtywhsnocb.html

int size() const noexcept { return n_; }
来源：http://dali.dashuyun.cn/Article/details/gtlabblwxx.html

[S53] C++：移动语义
来源：http://dali.yongpay.top/Article/details/gtbgtotsyb.html

std::vector<int> w = std::move(v);
来源：http://dali.yuxming.cn/Article/details/gtjynixjmu.html

[S54] C++：异常处理
来源：http://dali.pycfn.com/Article/details/gtacegltar.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xinyue.icu/Article/details/gtlgjacanv.html

[S55] C++：结构化绑定
来源：http://dali.hammf.cn/Article/details/gtiifexhyq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jiagoushi.top/Article/details/gtpygsnzuu.html

[S56] C++：optional
来源：http://dali.dashuyun.cn/Article/details/gtqryxhlsw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.vqdsnc.cn/Article/details/gtwkzmloxo.html

[S57] C++：编译期常量
来源：http://dali.zhixingplan.top/Article/details/gtnyezcrgn.html

constexpr int N = 10;
来源：http://dali.snrcjt.cn/Article/details/gtfumskyjq.html

[S58] C++：命名空间
来源：http://dali.xylfe.cn/Article/details/gtlfigfkrz.html

namespace ns { int f() { return 1; } }
来源：http://dali.gogol.net.cn/Article/details/gtsgttdcmx.html

[S59] C++：静态断言
来源：http://dali.kuanghao11.cn/Article/details/gtmzmlhtex.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guannengcc.top/Article/details/gtgshnetlx.html

[S60] C++：遍历并删除元素
来源：http://dali.shangyingyoupin.top/Article/details/gtuqrpfdap.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yongpay.top/Article/details/gtlkgmxcnd.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtfxvsvymr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnxiangtu.top/Article/details/gtmnrqjgdw.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtjgdxjgzd.html

[T01] Kotlin：Hello World
来源：http://dali.fengsongda.top/Article/details/gtgzpqksyz.html

println("Hello")
来源：http://dali.smart0.xyz/Article/details/gtujhptoga.html

[T02] Kotlin：变量
来源：http://dali.gzhubu.top/Article/details/gtlqdqnnmi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tanke756.top/Article/details/gthrxieodo.html

[T03] Kotlin：字符串模板
来源：http://dali.zhengqikj.top/Article/details/gtehqkilzl.html

"值: $b"
来源：http://dali.cqqwz.cn/Article/details/gtnkdgprnp.html

[T04] Kotlin：空安全
来源：http://dali.chenjidiqi.icu/Article/details/gtctgsxrzr.html

val n: String? = null;  n?.length
来源：http://dali.vqdsnc.cn/Article/details/gtxjyuzdig.html

[T05] Kotlin：when 表达式
来源：http://dali.mhx1999.top/Article/details/gtgojnuaqw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.fengsongda.top/Article/details/gtrgwuqram.html

[T06] Kotlin：集合映射
来源：http://dali.gzhubu.top/Article/details/gtwwjvvwuo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpnvappcp.html

[T07] Kotlin：集合过滤
来源：http://dali.xziqi.cn/Article/details/gttuusyqsk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jianghu66.top/Article/details/gttequfwpb.html

[T08] Kotlin：数据类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwcwlbed.html

data class User(val name: String, val age: Int)
来源：http://dali.shzxlz.cn/Article/details/gtadvfroyp.html

[T09] Kotlin：扩展函数
来源：http://dali.jiagoushi.top/Article/details/gtzetqdeus.html

fun String.exclaim() = this + "!"
来源：http://dali.yonumen.top/Article/details/gtdhfutxea.html

[T10] Kotlin：默认参数
来源：http://dali.0kj1m.cn/Article/details/gtndzziasj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jianghu66.top/Article/details/gteeovdkye.html

[T11] Kotlin：协程
来源：http://dali.aizwys.cn/Article/details/gtcdpbyxmr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.c1oappe.top/Article/details/gtvsoarejq.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqndwvxqs.html

val (a, b) = Pair(1, 2)
来源：http://dali.guannengcc.top/Article/details/gtjcxlnflc.html


<!-- 参考信息 -->