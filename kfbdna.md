代发 wailian999

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gtxjapofct.html

start) echo "启动" ;;
来源：http://dali.c1oappe.top/Article/details/gtqximhfeu.html

stop)  echo "停止" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtezdbywqv.html

*)     echo "未知命令" ;;
来源：http://dali.aizwys.cn/Article/details/gtfclpgyeu.html

esac
来源：http://dali.kuanghao11.cn/Article/details/gtqsgbhnzb.html

[R12] for 遍历文件
来源：http://dali.dashuyun.cn/Article/details/gtwvxzldre.html

for f in *.txt; do echo "$f"; done
来源：http://dali.havefunace.top/Article/details/gtrxbviiug.html

[R13] for 计数循环
来源：http://dali.nanxuanxn.top/Article/details/gtpgpszhcf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gtkgiwcuer.html

[R14] C 风格 for
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhawndna.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gtuoalqyss.html

[R15] while 逐行读文件
来源：http://dali.ivvv.top/Article/details/gttonnuubz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhixingplan.top/Article/details/gtouiqsmxd.html

[R16] until 等待条件
来源：http://dali.hnqzz.top/Article/details/gtyboooldg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gtwslajbfo.html

[R17] 数组定义与取值
来源：http://dali.yuanzhike.top/Article/details/gtpdxjlusa.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gzhubu.top/Article/details/gtxouoyutb.html

[R18] 遍历数组
来源：http://dali.yongpay.top/Article/details/gthifnoufq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhoulong.xyz/Article/details/gtvlovnrcf.html

[R19] 数组长度
来源：http://dali.316326.xyz/Article/details/gthcggcryd.html

echo "${#arr[@]}"
来源：http://dali.wangdashe.top/Article/details/gttqctqpcf.html

[R20] 关联数组（字典）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdmdqpfv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jianghu66.top/Article/details/gtlkqfzrtt.html

[R21] 字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gtjiqphqwp.html

echo "${#s}"
来源：http://dali.daria6918.cn/Article/details/gtumkwuyom.html

[R22] 截取子串
来源：http://dali.0kj1m.cn/Article/details/gtrfcneput.html

echo "${s:0:5}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwknfcle.html

[R23] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gtzhapquxp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xylfe.cn/Article/details/gtrlypgubh.html

[R24] 大小写转换
来源：http://dali.cheryme.top/Article/details/gtjnlqpyvg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hysaishi.cn/Article/details/gtmnywvklg.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxinkj.top/Article/details/gtczplyfld.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.316326.xyz/Article/details/gttqtbsabc.html

[R26] 命令替换
来源：http://dali.gogol.net.cn/Article/details/gttcapgezh.html

now=$(date +%F); echo "$now"
来源：http://dali.0kj1m.cn/Article/details/gtcduspcmu.html

[R27] 算术展开
来源：http://dali.gotoacloud.top/Article/details/gtkuusjztq.html

echo $((1 + 2 * 3))
来源：http://dali.zdqjudy.top/Article/details/gtphpsaqby.html

[R28] 浮点运算
来源：http://dali.gotoacloud.top/Article/details/gtwwjzwrcp.html

echo "scale=2; 10/3" | bc
来源：http://dali.aizwys.cn/Article/details/gtbvhmvlzu.html

[R29] 定义函数
来源：http://dali.gotoacloud.top/Article/details/gtwdlgjtns.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yongpay.top/Article/details/gtesqrfjsr.html

[R30] 函数返回状态码
来源：http://dali.ehwqpu.com/Article/details/gtcbyppudz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yanxiufei.cn/Article/details/gtuinhmmts.html

[R31] 局部变量
来源：http://dali.ivvv.top/Article/details/gtrbehqfdm.html

f() { local x=1; echo "$x"; }
来源：http://dali.daria6918.cn/Article/details/gtipmdnbnh.html

[R32] 参数个数校验
来源：http://dali.hammf.cn/Article/details/gttgkiybek.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinqigfzy.top/Article/details/gtzyhqdgid.html

[R33] 捕获错误并提示行号
来源：http://dali.hnxiangtu.top/Article/details/gtxannwjbp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hysaishi.cn/Article/details/gtgiueseau.html

[R34] 退出时清理
来源：http://dali.daxiang520.top/Article/details/gtmrmqebcj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gtdvwtahcw.html

[R35] 后台执行并等待
来源：http://dali.andypj.xyz/Article/details/gtaunezcpe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jiagoushi.top/Article/details/gtmxrixwhx.html

[R36] 并发执行多个任务
来源：http://dali.zhixingplan.top/Article/details/gtnabtasfe.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cashguo.top/Article/details/gtskyswflt.html

[R37] 把输出赋给变量
来源：http://dali.shuidangran.top/Article/details/gtypzktsdc.html

files=$(ls -1)
来源：http://dali.mhx1999.top/Article/details/gtwmsiimqk.html

[R38] 管道串联
来源：http://dali.cheryme.top/Article/details/gtsqpmsnlk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xziqi.cn/Article/details/gtbhristzw.html

[R39] 重定向标准输出与错误
来源：http://dali.jyoumei.cn/Article/details/gtynyizxcf.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gthrhsqbgx.html

[R40] 追加写日志
来源：http://dali.wangdashe.top/Article/details/gtqdtwiidy.html

echo "log" >> out.log
来源：http://dali.ppjwa.cn/Article/details/gtpwqiuiay.html

[R41] 丢弃输出
来源：http://dali.bjfxy.top/Article/details/gtgvdlnfky.html

cmd >/dev/null 2>&1
来源：http://dali.dianchejie.cn/Article/details/gtvfvwlvnr.html

[R42] 输入重定向
来源：http://dali.ydzc1.top/Article/details/gtdhnkbsqv.html

wc -l < a.txt
来源：http://dali.aizwys.cn/Article/details/gtdurphiaw.html

[R43] 按名字查找文件
来源：http://dali.fengsongda.top/Article/details/gtzwsrntap.html

find . -name "*.log" -type f
来源：http://dali.hywenlv.cn/Article/details/gtjascufmk.html

[R44] 按修改时间查找
来源：http://dali.haohaochexian.top/Article/details/gtqkislafs.html

find . -mtime -7 -type f
来源：http://dali.cdnleiting.top/Article/details/gtjyviushx.html

[R45] 批量删除
来源：http://dali.pycfn.com/Article/details/gtlkbcoxjd.html

find . -name "*.tmp" -delete
来源：http://dali.xinyue.icu/Article/details/gtplldxjjn.html

[R46] 递归替换文件内容
来源：http://dali.shzxlz.cn/Article/details/gtjuescixy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ehwqpu.com/Article/details/gtzwxvjzsv.html

[R47] sed 单行替换
来源：http://dali.zhiwuduotai.top/Article/details/gtjiajlpay.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuanzx.com/Article/details/gtmsuomhbm.html

[R48] awk 取指定列
来源：http://dali.jianghu66.top/Article/details/gtshkoeysh.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtydxsbfni.html

[R49] awk 带条件
来源：http://dali.yj20258.top/Article/details/gtlycdrjcv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.smart0.xyz/Article/details/gtswuwieuh.html

[R50] awk 求和
来源：http://dali.xylfe.cn/Article/details/gtjvdwunhx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xinyue.icu/Article/details/gtxtdzlclg.html

[R51] 排序去重取前几
来源：http://dali.zhengqikj.top/Article/details/gturygpkch.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aibaodan.cn/Article/details/gtklqjtjgr.html

[R52] 统计行数
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqtsxgnm.html

wc -l a.txt
来源：http://dali.gotoacloud.top/Article/details/gtvuyrcxud.html

[R53] 查看文件头与实时尾
来源：http://dali.tanke756.top/Article/details/gtnacudaek.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aibaodan.cn/Article/details/gtrzeuoehe.html

[R54] 比较两个文件
来源：http://dali.jqgfzy.top/Article/details/gtnjhwtvcd.html

diff a.txt b.txt
来源：http://dali.yuanzhike.top/Article/details/gtljrvtzpp.html

[R55] 压缩与解压
来源：http://dali.svipenyu.cn/Article/details/gtlkxvnmhw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuetiantiany.cn/Article/details/gtzrquekbc.html

[R56] 远程拷贝
来源：http://dali.yueranfly.top/Article/details/gtukqpknkl.html

scp file user@host:/path/
来源：http://dali.yueranfly.top/Article/details/gtqvqyoemf.html

[R57] 远程执行命令
来源：http://dali.316326.xyz/Article/details/gtvbviuubm.html

ssh user@host 'uptime'
来源：http://dali.hywenlv.cn/Article/details/gtlvycwmmk.html

[R58] 下载文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrkazyvf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yongpay.top/Article/details/gtssnrmcvh.html

[R59] 发 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtqzhbhxwa.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.daxiang520.top/Article/details/gtlzqnubic.html

[R60] 只看 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gtblprkanj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinqigfzy.top/Article/details/gtltmgsmaz.html

[R61] 磁盘占用
来源：http://dali.hammf.cn/Article/details/gtnzphpsjc.html

df -h;  du -sh *
来源：http://dali.zhongyouzk.top/Article/details/gtbthzinxm.html

[R62] 找最占空间的文件
来源：http://dali.jqgufenzy.top/Article/details/gtprfsyvar.html

du -ah . | sort -rh | head -10
来源：http://dali.c1oappe.top/Article/details/gtujytjohh.html

[R63] 内存与进程
来源：http://dali.daxiang520.top/Article/details/gtizgcigrt.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxuanxn.top/Article/details/gtnslulhaz.html

[R64] 结束进程
来源：http://dali.jinqigfzy.top/Article/details/gtgghgbmmx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinghuilouyu.cn/Article/details/gttpkchbqc.html

[R65] 查看端口占用
来源：http://dali.jqgufenzy.top/Article/details/gtzqztjvhw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jianghu66.top/Article/details/gtwlahqinj.html

[R66] 定时任务
来源：http://dali.nwbrower.top/Article/details/gtmyrsuwjv.html

crontab -e;  crontab -l
来源：http://dali.dashuyun.cn/Article/details/gtmdxwbuzv.html

[R67] 生成随机十六进制串
来源：http://dali.pycfn.com/Article/details/gttaslmpib.html

openssl rand -hex 16
来源：http://dali.tanke756.top/Article/details/gtejnfjhnv.html

[R68] 计算文件校验值
来源：http://dali.0kj1m.cn/Article/details/gtnmxtbbxa.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ybcxt.top/Article/details/gtdegcftet.html

[R69] 生成随机密码
来源：http://dali.jqgfzy.top/Article/details/gthrqturek.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinghuilouyu.cn/Article/details/gtkztwlapj.html

[R70] 时间戳与互转
来源：http://dali.316326.xyz/Article/details/gtxfmqupxp.html

date +%s;  date -d @1700000000
来源：http://dali.meibo888.top/Article/details/gtolakhjqm.html

[R71] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gtmaasgskn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuetiantiany.cn/Article/details/gtkjrnldty.html

[R72] 等待端口就绪
来源：http://dali.pengpengdd.cyou/Article/details/gtrfvkqvmo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gtfkepiasr.html

[R73] 分割大日志
来源：http://dali.zhengqikj.top/Article/details/gtotaerasl.html

split -l 1000 big.log part_
来源：http://dali.chenlongwang.top/Article/details/gtwijbwdgz.html

[R74] 批量重命名
来源：http://dali.xuanzx.com/Article/details/gtnyynpwsh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tian-w.cn/Article/details/gtspnnhbia.html

[R75] 导出环境变量
来源：http://dali.jqgfzy.top/Article/details/gtarulgbet.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.svipenyu.cn/Article/details/gtpyzxzwgh.html

[R76] 使用临时文件
来源：http://dali.gaohongyu789.top/Article/details/gtirenvsor.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gtgeqpsmgo.html

[R77] 读取用户输入
来源：http://dali.ppjwa.cn/Article/details/gtnxchfjmw.html

read -rp "请输入: " ans
来源：http://dali.gzhubu.top/Article/details/gtqfgrvsun.html

[R78] 交互式菜单
来源：http://dali.xziqi.cn/Article/details/gtzcrhpugi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxuanxn.top/Article/details/gtxcjdmvqe.html

[R79] 解析命令行选项
来源：http://dali.yj202588.top/Article/details/gtfhcfsjze.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.mhx1999.top/Article/details/gtxfjietuh.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gttnziuoub.html

time ./run.sh
来源：http://dali.0kj1m.cn/Article/details/gtxvfnpehr.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtlrmvapcv.html

S. C / C++ 专题
来源：http://dali.sxryk.cn/Article/details/gtcblgzmjd.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtwkikvewk.html

[S01] C：Hello World
来源：http://dali.ybcxt.top/Article/details/gtquywnrzd.html

#include <stdio.h>
来源：http://dali.havefunace.top/Article/details/gtlacwdzqd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigfzy.top/Article/details/gtjptyifzt.html

[S02] C：变量与格式化输出
来源：http://dali.yonumen.top/Article/details/gtvcigmlcd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhengqikj.top/Article/details/gtjkeyxluj.html

[S03] C：读入整数
来源：http://dali.snrcjt.cn/Article/details/gtxgztqmpc.html

int x; scanf("%d", &x);
来源：http://dali.jianghu66.top/Article/details/gtajzlkcwj.html

[S04] C：字符串复制
来源：http://dali.cdnleiting.top/Article/details/gttsrixscm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pycfn.com/Article/details/gtjhjgzfkh.html

[S05] C：字符串长度
来源：http://dali.andypj.xyz/Article/details/gtvyvmymig.html

strlen(s)
来源：http://dali.sufxvd.cn/Article/details/gtwkekpvcx.html

[S06] C：字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtcnjbavut.html

strcmp(a, b) == 0
来源：http://dali.316326.xyz/Article/details/gtjrwdskts.html

[S07] C：数组遍历求和
来源：http://dali.xuanzx.com/Article/details/gtobewoyjl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ehwqpu.com/Article/details/gtgkqzyfls.html

[S08] C：动态内存分配与释放
来源：http://dali.tian-w.cn/Article/details/gtezimqmpj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cashguo.top/Article/details/gtyzyzoerp.html

[S09] C：结构体定义与初始化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftzkefyp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.iojbl.cn/Article/details/gttmuzvuik.html

[S10] C：指针与解引用
来源：http://dali.zycfv.cn/Article/details/gtkhiqwklx.html

int *p = &a;  *p = 5;
来源：http://dali.xinyue.icu/Article/details/gtljqrkrzy.html

[S11] C：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gttthomxqv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuetiantiany.cn/Article/details/gtossjhdzl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shzxlz.cn/Article/details/gtszpbivrl.html

fclose(f);
来源：http://dali.cdnleiting.top/Article/details/gthpsvoyxo.html

[S12] C：写文件
来源：http://dali.nwbrower.top/Article/details/gtbpepbppa.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gthxatcavs.html

[S13] C：宏定义
来源：http://dali.ehwqpu.com/Article/details/gthxzpxokg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yueranfly.top/Article/details/gtvnbnxkvt.html

[S14] C：枚举
来源：http://dali.yonumen.top/Article/details/gtcjzgmvuv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gtmlmsjgxw.html

[S15] C：类型转换
来源：http://dali.hywenlv.cn/Article/details/gtftzoibdl.html

(double) a / b
来源：http://dali.xinyue.icu/Article/details/gtmmkeghtl.html

[S16] C：位操作置位
来源：http://dali.sufxvd.cn/Article/details/gtvjnavwhb.html

x |= (1 << 3);
来源：http://dali.dianchejie.cn/Article/details/gtibkxijfr.html

[S17] C：安全拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtiuhgjvzy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.iojbl.cn/Article/details/gtboantsfy.html

[S18] C：命令行参数
来源：http://dali.svipenyu.cn/Article/details/gttcyqxlct.html

int main(int argc, char **argv)
来源：http://dali.hongshengwenyu.top/Article/details/gtvkuoquft.html

[S19] C：快速排序
来源：http://dali.guannengcc.top/Article/details/gtrzcnjdkv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenzaomai.com/Article/details/gtubsqefjk.html

[S20] C：二分查找
来源：http://dali.ydzc1.top/Article/details/gtewakfsxj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagmxrgnz.html

[S21] C：字符类别判断
来源：http://dali.hnxiangtu.top/Article/details/gtquhxbjfp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hongshengwenyu.top/Article/details/gtajcawhmz.html

[S22] C：字符串转数字
来源：http://dali.quarkkingdee.top/Article/details/gtvpdyotqa.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jyoumei.cn/Article/details/gtrqeheauj.html

[S23] C：随机数
来源：http://dali.pengpengdd.cyou/Article/details/gtrneohvxl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.9152youxi.cn/Article/details/gtwhpbpdtf.html

[S24] C：获取本地时间
来源：http://dali.ivvv.top/Article/details/gtkqebhjfx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.svipenyu.cn/Article/details/gtlrqkynwq.html

[S25] C：内存拷贝
来源：http://dali.vqdsnc.cn/Article/details/gtuiszthvw.html

memcpy(dst, src, n);
来源：http://dali.daxiang520.top/Article/details/gtizyjronw.html

[S26] C：内存清零
来源：http://dali.yonumen.top/Article/details/gtiyxydkdy.html

memset(a, 0, sizeof a);
来源：http://dali.pycfn.com/Article/details/gtjokyfdrf.html

[S27] C：定义常量
来源：http://dali.gotoacloud.top/Article/details/gtprtbjebi.html

const double PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtluxjjgky.html

[S28] C：静态变量
来源：http://dali.zhoulong.xyz/Article/details/gtbvuqjzye.html

static int counter = 0;
来源：http://dali.zycfv.cn/Article/details/gtyqtevvct.html

[S29] C：变参函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gttoutytxh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxuanxn.top/Article/details/gtfcdbjtss.html

[S30] C：头文件保护
来源：http://dali.hysaishi.cn/Article/details/gtjotcjolf.html

#ifndef X_H
来源：http://dali.yueranfly.top/Article/details/gtdxwcsrit.html

#define X_H
来源：http://dali.ydzc1.top/Article/details/gtwlulyrfn.html

#endif
来源：http://dali.hongshengwenyu.top/Article/details/gtrzoglcwy.html

[S31] C++：Hello World
来源：http://dali.smart0.xyz/Article/details/gttozcvtqx.html

#include <iostream>
来源：http://dali.cheryme.top/Article/details/gtccsuvbuf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xinyue.icu/Article/details/gtcedmxcob.html

[S32] C++：字符串
来源：http://dali.hysaishi.cn/Article/details/gtzwqgisiv.html

std::string s = "hi";  s += "!";
来源：http://dali.tianlin.xyz/Article/details/gtoqtdlxkw.html

[S33] C++：vector 增删
来源：http://dali.kuanghao11.cn/Article/details/gtadicwisr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcohfiiz.html

[S34] C++：遍历 vector
来源：http://dali.sufxvd.cn/Article/details/gtuqwxbnrz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xziqi.cn/Article/details/gtozvqelwf.html

[S35] C++：map
来源：http://dali.hongshengwenyu.top/Article/details/gtayxaodvd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtmepsyruj.html

[S36] C++：unordered_map
来源：http://dali.zycfv.cn/Article/details/gtdvxkyyli.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ivvv.top/Article/details/gtpvfyigml.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gttaedbdkj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenlongwang.top/Article/details/gtjhkabqus.html

[S38] C++：排序
来源：http://dali.c1oappe.top/Article/details/gtsccscdja.html

std::sort(v.begin(), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnnobfzs.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgfzy.top/Article/details/gttuzeduaz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqyblihxc.html

[S40] C++：查找元素
来源：http://dali.dianchejie.cn/Article/details/gttktiomzv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenzaomai.com/Article/details/gtpkdrjlpb.html

[S41] C++：类与构造函数
来源：http://dali.sweek.top/Article/details/gtoqtuzgsk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.quarkkingdee.top/Article/details/gtrnrqwmtr.html

[S42] C++：继承与虚函数
来源：http://dali.ppjwa.cn/Article/details/gtpdyxtjit.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhoulong.xyz/Article/details/gtiqlzpgqd.html

[S43] C++：智能指针
来源：http://dali.sufxvd.cn/Article/details/gtwmkzvgvu.html

auto p = std::make_unique<int>(5);
来源：http://dali.c1oappe.top/Article/details/gtgkmrgujz.html

[S44] C++：引用传参
来源：http://dali.jlsjyb.cn/Article/details/gtzrhccxkg.html

void inc(int &x) { ++x; }
来源：http://dali.guannengcc.top/Article/details/gtajqqljha.html

[S45] C++：lambda
来源：http://dali.shangyingyoupin.top/Article/details/gtocrdwumn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hnxiangtu.top/Article/details/gtgknytonk.html

[S46] C++：函数模板
来源：http://dali.ybcxt.top/Article/details/gtyvewhyaa.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ppjwa.cn/Article/details/gtoqssqrls.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtlquzwaoq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxuanxn.top/Article/details/gtmjqluwkn.html

[S48] C++：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gttesrbrpa.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhiwuduotai.top/Article/details/gtgncmtxmb.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigfzy.top/Article/details/gtxkpvhovh.html

[S49] C++：写文件
来源：http://dali.yangfankeji.com/Article/details/gtpjnjkxpj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.mhx1999.top/Article/details/gtrazqvlds.html

[S50] C++：格式化数字
来源：http://dali.vqdsnc.cn/Article/details/gtycndnthk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ivvv.top/Article/details/gtfzfnmnvf.html

[S51] C++：显式类型转换
来源：http://dali.shzxlz.cn/Article/details/gtuaougjsw.html

static_cast<double>(a) / b
来源：http://dali.yuanzhike.top/Article/details/gtrbxrkutx.html

[S52] C++：const 与 noexcept
来源：http://dali.tianlin.xyz/Article/details/gtsqehdfuo.html

int size() const noexcept { return n_; }
来源：http://dali.gotoacloud.top/Article/details/gtftvfcxhf.html

[S53] C++：移动语义
来源：http://dali.316326.xyz/Article/details/gttxgostbh.html

std::vector<int> w = std::move(v);
来源：http://dali.tian-w.cn/Article/details/gtszsxatou.html

[S54] C++：异常处理
来源：http://dali.jiagoushi.top/Article/details/gtiqqdorvu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jyoumei.cn/Article/details/gtupzyvulo.html

[S55] C++：结构化绑定
来源：http://dali.iojbl.cn/Article/details/gtiemcwjvj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nwbrower.top/Article/details/gtwexlzyjh.html

[S56] C++：optional
来源：http://dali.cheryme.top/Article/details/gtysjxsoxj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jyoumei.cn/Article/details/gtfchlqyud.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gthlebvvqo.html

constexpr int N = 10;
来源：http://dali.gogol.net.cn/Article/details/gtfzgjoydk.html

[S58] C++：命名空间
来源：http://dali.smart0.xyz/Article/details/gtwwfxwzhk.html

namespace ns { int f() { return 1; } }
来源：http://dali.cqqwz.cn/Article/details/gtqbeuocdi.html

[S59] C++：静态断言
来源：http://dali.guowangkeji.top/Article/details/gtxyfacnua.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhoulong.xyz/Article/details/gtojvvdfof.html

[S60] C++：遍历并删除元素
来源：http://dali.gotoacloud.top/Article/details/gtfxepwnmb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gtcbgbndwg.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtiuwoaljh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ppjwa.cn/Article/details/gtaaipjylr.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtasveasrn.html

[T01] Kotlin：Hello World
来源：http://dali.c1oappe.top/Article/details/gtjlztaytk.html

println("Hello")
来源：http://dali.fengsongda.top/Article/details/gtblugrmil.html

[T02] Kotlin：变量
来源：http://dali.hywenlv.cn/Article/details/gtiybxykwa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hfpthk.cn/Article/details/gtsthncqus.html

[T03] Kotlin：字符串模板
来源：http://dali.birdmap.top/Article/details/gtuhacukhd.html

"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttgtulhuf.html

[T04] Kotlin：空安全
来源：http://dali.yuxming.cn/Article/details/gtxuzelgnv.html

val n: String? = null;  n?.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafvcucqw.html

[T05] Kotlin：when 表达式
来源：http://dali.hnqzz.top/Article/details/gtmezqdqag.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jianghu66.top/Article/details/gtizcarfpt.html

[T06] Kotlin：集合映射
来源：http://dali.jinqigfzy.top/Article/details/gtdzwlfcua.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuanzx.com/Article/details/gtppoesswv.html

[T07] Kotlin：集合过滤
来源：http://dali.zhoulong.xyz/Article/details/gtzkqfxxor.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yongpay.top/Article/details/gtxhzbglyt.html

[T08] Kotlin：数据类
来源：http://dali.316326.xyz/Article/details/gtwaynpvsm.html

data class User(val name: String, val age: Int)
来源：http://dali.birdmap.top/Article/details/gtlzkstvcn.html

[T09] Kotlin：扩展函数
来源：http://dali.yvedp.cn/Article/details/gtosfujqpk.html

fun String.exclaim() = this + "!"
来源：http://dali.gzhubu.top/Article/details/gtfdeugrjy.html

[T10] Kotlin：默认参数
来源：http://dali.yanxiufei.cn/Article/details/gtrnzlkklo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.andypj.xyz/Article/details/gtsexllzyt.html

[T11] Kotlin：协程
来源：http://dali.smart0.xyz/Article/details/gtiiyoupwd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gaohongyu789.top/Article/details/gtaprcpqhm.html

[T12] Kotlin：解构声明
来源：http://dali.ybcxt.top/Article/details/gtfjvrqfcj.html

val (a, b) = Pair(1, 2)
来源：http://dali.xylfe.cn/Article/details/gtzooxraib.html


<!-- 参考信息 -->