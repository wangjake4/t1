代发 wailian999

esac
来源：http://dali.sufxvd.cn/Article/details/gtassgmyii.html

[R12] for 遍历文件
来源：http://dali.gogol.net.cn/Article/details/gtcymlgwax.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sweek.top/Article/details/gtrbtflcfk.html

[R13] for 计数循环
来源：http://dali.xylfe.cn/Article/details/gtmtzuljgc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgufenzy.top/Article/details/gtbmwuvkix.html

[R14] C 风格 for
来源：http://dali.xuanzx.com/Article/details/gtoxnzjred.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gtxkqmfpjc.html

[R15] while 逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtxlwypmca.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gaohongyu789.top/Article/details/gtgrcgpooj.html

[R16] until 等待条件
来源：http://dali.yanxiufei.cn/Article/details/gtvfvotget.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkjegvlo.html

[R17] 数组定义与取值
来源：http://dali.zhiwuduotai.top/Article/details/gttoudtxhe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.dianchejie.cn/Article/details/gticrkccmk.html

[R18] 遍历数组
来源：http://dali.ybcxt.top/Article/details/gtclioemxu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jyoumei.cn/Article/details/gtwlssfmtk.html

[R19] 数组长度
来源：http://dali.redwolf501.top/Article/details/gtkkhxvpti.html

echo "${#arr[@]}"
来源：http://dali.haohaochexian.top/Article/details/gtgldnqukl.html

[R20] 关联数组（字典）
来源：http://dali.shuidangran.top/Article/details/gtggwbfkcv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnxiangtu.top/Article/details/gtugfolqgl.html

[R21] 字符串长度
来源：http://dali.ivvv.top/Article/details/gtbnnpylfo.html

echo "${#s}"
来源：http://dali.yueranfly.top/Article/details/gtzzfbwirr.html

[R22] 截取子串
来源：http://dali.yueranfly.top/Article/details/gtmxcsomcq.html

echo "${s:0:5}"
来源：http://dali.cdnleiting.top/Article/details/gtdszmlhjn.html

[R23] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gtyemzkkyg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxutntno.html

[R24] 大小写转换
来源：http://dali.yj20258.top/Article/details/gtoytdthmw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgisvphk.html

[R25] 去后缀 / 去前缀
来源：http://dali.hysaishi.cn/Article/details/gtlnhngqmp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgufenzy.top/Article/details/gttzqtzbev.html

[R26] 命令替换
来源：http://dali.daria6918.cn/Article/details/gtggchftxm.html

now=$(date +%F); echo "$now"
来源：http://dali.sysykeji.top/Article/details/gtmyeocwhp.html

[R27] 算术展开
来源：http://dali.zhiwuduotai.top/Article/details/gtxeuhfuyn.html

echo $((1 + 2 * 3))
来源：http://dali.nanxinkj.top/Article/details/gtvhjojnbe.html

[R28] 浮点运算
来源：http://dali.jyoumei.cn/Article/details/gthqwogxah.html

echo "scale=2; 10/3" | bc
来源：http://dali.smart0.xyz/Article/details/gtusqjptcl.html

[R29] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gtfncmnint.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hywenlv.cn/Article/details/gtcdomijas.html

[R30] 函数返回状态码
来源：http://dali.fengsongda.top/Article/details/gtoldbnvle.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgfzy.top/Article/details/gtmbwlupui.html

[R31] 局部变量
来源：http://dali.wangdashe.top/Article/details/gteezngplp.html

f() { local x=1; echo "$x"; }
来源：http://dali.sxryk.cn/Article/details/gtgkoayxmx.html

[R32] 参数个数校验
来源：http://dali.feifeiyinyue.top/Article/details/gtxjmeidug.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gtlnqjwrvt.html

[R33] 捕获错误并提示行号
来源：http://dali.9152youxi.cn/Article/details/gtkpaczcdv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nwbrower.top/Article/details/gtmsnkqzwq.html

[R34] 退出时清理
来源：http://dali.feifeiyinyue.top/Article/details/gtbmeisumj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gtwtrbpchv.html

[R35] 后台执行并等待
来源：http://dali.sxryk.cn/Article/details/gtvlckrxmd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guannengcc.top/Article/details/gtnnaosgfx.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfiosftg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yueranfly.top/Article/details/gthecmtkmm.html

[R37] 把输出赋给变量
来源：http://dali.ydzc1.top/Article/details/gtxsmfgctb.html

files=$(ls -1)
来源：http://dali.quarkkingdee.top/Article/details/gtovswwtqa.html

[R38] 管道串联
来源：http://dali.jinghuilouyu.cn/Article/details/gtdllrtvoa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.bjfxy.top/Article/details/gtkhxakrmi.html

[R39] 重定向标准输出与错误
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzxgwjgy.html

cmd > out.log 2>&1
来源：http://dali.guannengcc.top/Article/details/gtltsdwssy.html

[R40] 追加写日志
来源：http://dali.meibo888.top/Article/details/gtnbkvptly.html

echo "log" >> out.log
来源：http://dali.yongpay.top/Article/details/gtdynxotgw.html

[R41] 丢弃输出
来源：http://dali.ivvv.top/Article/details/gtyamswrxb.html

cmd >/dev/null 2>&1
来源：http://dali.hammf.cn/Article/details/gtjeduepnf.html

[R42] 输入重定向
来源：http://dali.cheryme.top/Article/details/gtqjojrwyn.html

wc -l < a.txt
来源：http://dali.nwbrower.top/Article/details/gtmztmkggd.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gtkdaovfqn.html

find . -name "*.log" -type f
来源：http://dali.hywenlv.cn/Article/details/gtcwagfzio.html

[R44] 按修改时间查找
来源：http://dali.pycfn.com/Article/details/gtsjgwcfck.html

find . -mtime -7 -type f
来源：http://dali.hongshengwenyu.top/Article/details/gtikquhqbs.html

[R45] 批量删除
来源：http://dali.dashuyun.cn/Article/details/gtnauwkqth.html

find . -name "*.tmp" -delete
来源：http://dali.havefunace.top/Article/details/gtvxlkjyqd.html

[R46] 递归替换文件内容
来源：http://dali.shuidangran.top/Article/details/gtbhdgcblh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.316326.xyz/Article/details/gtyewnuyyz.html

[R47] sed 单行替换
来源：http://dali.316326.xyz/Article/details/gtfommfvky.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hfpthk.cn/Article/details/gthxyrobtt.html

[R48] awk 取指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuemwjepe.html

awk '{print $1, $3}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gtwmvolgdi.html

[R49] awk 带条件
来源：http://dali.shuidangran.top/Article/details/gtpfrvxgnl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xziqi.cn/Article/details/gtfpidbjbe.html

[R50] awk 求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybeuhcto.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ydzc1.top/Article/details/gtzptchwcm.html

[R51] 排序去重取前几
来源：http://dali.xylfe.cn/Article/details/gtglpgvhxt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ydzc1.top/Article/details/gtamqtmnme.html

[R52] 统计行数
来源：http://dali.sxryk.cn/Article/details/gtwtztzggs.html

wc -l a.txt
来源：http://dali.xziqi.cn/Article/details/gtrtehkhlg.html

[R53] 查看文件头与实时尾
来源：http://dali.havefunace.top/Article/details/gtymoxftui.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.dianchejie.cn/Article/details/gttuwgvxol.html

[R54] 比较两个文件
来源：http://dali.ydzc1.top/Article/details/gtqxyynoda.html

diff a.txt b.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtslabgikj.html

[R55] 压缩与解压
来源：http://dali.xinyue.icu/Article/details/gtmjjozkcp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jlsjyb.cn/Article/details/gtodozvzsm.html

[R56] 远程拷贝
来源：http://dali.zhengqikj.top/Article/details/gtfgfkvscz.html

scp file user@host:/path/
来源：http://dali.hammf.cn/Article/details/gtccjbhlrt.html

[R57] 远程执行命令
来源：http://dali.andypj.xyz/Article/details/gtjqllescf.html

ssh user@host 'uptime'
来源：http://dali.hnqzz.top/Article/details/gtxlchjkoa.html

[R58] 下载文件
来源：http://dali.zhoulong.xyz/Article/details/gtgnnybqdh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yongpay.top/Article/details/gtkogxqxka.html

[R59] 发 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gthibesolh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuetiantiany.cn/Article/details/gtbwnofuco.html

[R60] 只看 HTTP 状态码
来源：http://dali.gaohongyu789.top/Article/details/gtoannsiqc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.quarkkingdee.top/Article/details/gticattdnc.html

[R61] 磁盘占用
来源：http://dali.wangshuangyany.cn/Article/details/gtmoileiny.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gthkqczqex.html

[R62] 找最占空间的文件
来源：http://dali.hnqzz.top/Article/details/gtkyyzangz.html

du -ah . | sort -rh | head -10
来源：http://dali.ivvv.top/Article/details/gtqhrpdxll.html

[R63] 内存与进程
来源：http://dali.jianghu66.top/Article/details/gtaorcjobh.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxinkj.top/Article/details/gtqnlianfw.html

[R64] 结束进程
来源：http://dali.guowangkeji.top/Article/details/gtbyheislo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shzxlz.cn/Article/details/gtrypjrblv.html

[R65] 查看端口占用
来源：http://dali.hywenlv.cn/Article/details/gtmsuosmyo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shuidangran.top/Article/details/gttwnyogdt.html

[R66] 定时任务
来源：http://dali.wangdashe.top/Article/details/gtrxewytuy.html

crontab -e;  crontab -l
来源：http://dali.andypj.xyz/Article/details/gtuusklsmh.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcacmito.html

openssl rand -hex 16
来源：http://dali.hammf.cn/Article/details/gtrwxttmvr.html

[R68] 计算文件校验值
来源：http://dali.nanxuanxn.top/Article/details/gtowwkzsbk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guowangkeji.top/Article/details/gtfxwwyhkm.html

[R69] 生成随机密码
来源：http://dali.tian-w.cn/Article/details/gtwwooxsob.html

head -c 16 /dev/urandom | base64
来源：http://dali.ydzc1.top/Article/details/gtukjtqccl.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangtech.top/Article/details/gtryadhmhd.html

date +%s;  date -d @1700000000
来源：http://dali.sufxvd.cn/Article/details/gtpblwubke.html

[R71] 日期格式化
来源：http://dali.wangdashe.top/Article/details/gtxlocruop.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xziqi.cn/Article/details/gtofxchbnd.html

[R72] 等待端口就绪
来源：http://dali.sxryk.cn/Article/details/gtkxxwmcwb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gtaacjfnik.html

[R73] 分割大日志
来源：http://dali.aibaodan.cn/Article/details/gtgsppjwsz.html

split -l 1000 big.log part_
来源：http://dali.ehwqpu.com/Article/details/gtzsatepuv.html

[R74] 批量重命名
来源：http://dali.vqdsnc.cn/Article/details/gtadfnmnxw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkccvgoto.html

[R75] 导出环境变量
来源：http://dali.dianchejie.cn/Article/details/gtnzqddjvk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.meibo888.top/Article/details/gtfyohczul.html

[R76] 使用临时文件
来源：http://dali.316326.xyz/Article/details/gtsxgkqcqx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gtrmjnbbxl.html

[R77] 读取用户输入
来源：http://dali.pycfn.com/Article/details/gtbgwfpkga.html

read -rp "请输入: " ans
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqefyvknf.html

[R78] 交互式菜单
来源：http://dali.yangfankeji.com/Article/details/gtuernxmwi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.feifeiyinyue.top/Article/details/gtekhunboh.html

[R79] 解析命令行选项
来源：http://dali.sufxvd.cn/Article/details/gtjejkygig.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pycfn.com/Article/details/gtoedypomm.html

[R80] 查看脚本执行耗时
来源：http://dali.daria6918.cn/Article/details/gtnqrocgyg.html

time ./run.sh
来源：http://dali.jiagoushi.top/Article/details/gtjygxqlzw.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtewujbyow.html

S. C / C++ 专题
来源：http://dali.jinqigufen.top/Article/details/gtmoyyvxlv.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtmrybwfeh.html

[S01] C：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtmwyrfgmv.html

#include <stdio.h>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjftutrx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxoixvfw.html

[S02] C：变量与格式化输出
来源：http://dali.aizwys.cn/Article/details/gthsazifug.html

int a = 10; printf("%d\n", a);
来源：http://dali.316326.xyz/Article/details/gtqqveatcq.html

[S03] C：读入整数
来源：http://dali.sysykeji.top/Article/details/gtbwnfcbyt.html

int x; scanf("%d", &x);
来源：http://dali.ppjwa.cn/Article/details/gtvdomzawd.html

[S04] C：字符串复制
来源：http://dali.fengsongda.top/Article/details/gtpeuitirk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtyjdsrgbb.html

[S05] C：字符串长度
来源：http://dali.tianlin.xyz/Article/details/gtdvfhgwxz.html

strlen(s)
来源：http://dali.svipenyu.cn/Article/details/gtvjqturqf.html

[S06] C：字符串比较
来源：http://dali.redwolf501.top/Article/details/gtqvptelfg.html

strcmp(a, b) == 0
来源：http://dali.xuanzx.com/Article/details/gtmfkyiyse.html

[S07] C：数组遍历求和
来源：http://dali.ybcxt.top/Article/details/gtvbzmulev.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ydzc1.top/Article/details/gtygqjygjs.html

[S08] C：动态内存分配与释放
来源：http://dali.xuetiantiany.cn/Article/details/gtexxfuwtl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hongshengwenyu.top/Article/details/gtorxffgxs.html

[S09] C：结构体定义与初始化
来源：http://dali.jiagoushi.top/Article/details/gtrgwzcjkt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.bjfxy.top/Article/details/gtrfrjdmsw.html

[S10] C：指针与解引用
来源：http://dali.aibaodan.cn/Article/details/gtpmmpmgrd.html

int *p = &a;  *p = 5;
来源：http://dali.pycfn.com/Article/details/gtsfdwesgn.html

[S11] C：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtkzuvclat.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tianlin.xyz/Article/details/gtjptkhzuw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ivvv.top/Article/details/gtvjtxierr.html

fclose(f);
来源：http://dali.zhongyouzk.top/Article/details/gtlxyncgec.html

[S12] C：写文件
来源：http://dali.haohaochexian.top/Article/details/gtknmjiapx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gtdhncipvq.html

[S13] C：宏定义
来源：http://dali.shzxlz.cn/Article/details/gtndixktvv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangshuangyany.cn/Article/details/gtnufahbdp.html

[S14] C：枚举
来源：http://dali.svipenyu.cn/Article/details/gtgrbfxaxl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jiagoushi.top/Article/details/gtudyomrwd.html

[S15] C：类型转换
来源：http://dali.sysykeji.top/Article/details/gtjbcwkowm.html

(double) a / b
来源：http://dali.fzhhl.top/Article/details/gttoselutt.html

[S16] C：位操作置位
来源：http://dali.zhixingplan.top/Article/details/gtwxbwuobt.html

x |= (1 << 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwbaqkuf.html

[S17] C：安全拼接字符串
来源：http://dali.zycfv.cn/Article/details/gtrofhtrik.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shzxlz.cn/Article/details/gtjofnsjuo.html

[S18] C：命令行参数
来源：http://dali.svipenyu.cn/Article/details/gtjzjcypae.html

int main(int argc, char **argv)
来源：http://dali.cheryme.top/Article/details/gtmomkjpuy.html

[S19] C：快速排序
来源：http://dali.iojbl.cn/Article/details/gtwwzjmokz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jyoumei.cn/Article/details/gtbxfpaxvn.html

[S20] C：二分查找
来源：http://dali.kuanghao11.cn/Article/details/gtfaxmrjjr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gtklsxqljh.html

[S21] C：字符类别判断
来源：http://dali.xinyue.icu/Article/details/gtoeshohfw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zycfv.cn/Article/details/gtahtumheq.html

[S22] C：字符串转数字
来源：http://dali.yj20258888.top/Article/details/gtwklhdzio.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shuidangran.top/Article/details/gtklvoyust.html

[S23] C：随机数
来源：http://dali.xuanzx.com/Article/details/gtfhnycgux.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fengsongda.top/Article/details/gtkzjmuqxx.html

[S24] C：获取本地时间
来源：http://dali.guowangkeji.top/Article/details/gtiiwrvdbm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jqgufenzy.top/Article/details/gttmfyocic.html

[S25] C：内存拷贝
来源：http://dali.zycfv.cn/Article/details/gtqlgwlhps.html

memcpy(dst, src, n);
来源：http://dali.aibaodan.cn/Article/details/gtltgnipsp.html

[S26] C：内存清零
来源：http://dali.c1oappe.top/Article/details/gtmlxqurwv.html

memset(a, 0, sizeof a);
来源：http://dali.cdnleiting.top/Article/details/gtattkvbca.html

[S27] C：定义常量
来源：http://dali.gaohongyu789.top/Article/details/gtrieebvjj.html

const double PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtmvjyafes.html

[S28] C：静态变量
来源：http://dali.mhx1999.top/Article/details/gthvkrktto.html

static int counter = 0;
来源：http://dali.yj20258888.top/Article/details/gtcctndytx.html

[S29] C：变参函数
来源：http://dali.fzhhl.top/Article/details/gtlqjghakz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xinyue.icu/Article/details/gtthmoqkkb.html

[S30] C：头文件保护
来源：http://dali.xuanzx.com/Article/details/gtpbzxvehi.html

#ifndef X_H
来源：http://dali.vqdsnc.cn/Article/details/gtayqstnfg.html

#define X_H
来源：http://dali.pycfn.com/Article/details/gtzxghuihs.html

#endif
来源：http://dali.guowangkeji.top/Article/details/gtcgcwigya.html

[S31] C++：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtksktpgsn.html

#include <iostream>
来源：http://dali.ppjwa.cn/Article/details/gtpzhojdtu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuanzhike.top/Article/details/gtpabhimvp.html

[S32] C++：字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtyztatzev.html

std::string s = "hi";  s += "!";
来源：http://dali.wangdashe.top/Article/details/gtqrabqxlk.html

[S33] C++：vector 增删
来源：http://dali.0kj1m.cn/Article/details/gtqdheuluu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yonumen.top/Article/details/gtvcoxsskk.html

[S34] C++：遍历 vector
来源：http://dali.guowangkeji.top/Article/details/gtbowhlrqq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gogol.net.cn/Article/details/gtkusyorrp.html

[S35] C++：map
来源：http://dali.yvedp.cn/Article/details/gttxcnrseh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtgbbnmyuv.html

[S36] C++：unordered_map
来源：http://dali.shuidangran.top/Article/details/gtvcqoflfw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtdfbxgzia.html

[S37] C++：set
来源：http://dali.yuanzhike.top/Article/details/gtgeqzypnl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yanxiufei.cn/Article/details/gtpcngbmva.html

[S38] C++：排序
来源：http://dali.feifeiyinyue.top/Article/details/gtdtmlpqvl.html

std::sort(v.begin(), v.end());
来源：http://dali.jiagoushi.top/Article/details/gtdnzudgtc.html

[S39] C++：自定义比较器排序
来源：http://dali.cucudq.cn/Article/details/gtpikyvntw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yvedp.cn/Article/details/gtirvvkmlw.html

[S40] C++：查找元素
来源：http://dali.hysaishi.cn/Article/details/gtntgtsnfs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ydzc1.top/Article/details/gtqqvqbiyo.html

[S41] C++：类与构造函数
来源：http://dali.smart0.xyz/Article/details/gtpgubrsby.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dashuyun.cn/Article/details/gtiycdpzcg.html

[S42] C++：继承与虚函数
来源：http://dali.smart0.xyz/Article/details/gtnqklbvub.html

class B : public Base { public: void f() override {} };
来源：http://dali.hongshengwenyu.top/Article/details/gtrnlnanru.html

[S43] C++：智能指针
来源：http://dali.pengpengdd.cyou/Article/details/gtimtkcitc.html

auto p = std::make_unique<int>(5);
来源：http://dali.dashuyun.cn/Article/details/gtgurdhety.html

[S44] C++：引用传参
来源：http://dali.gzhubu.top/Article/details/gtpoeoctrr.html

void inc(int &x) { ++x; }
来源：http://dali.ydzc1.top/Article/details/gtxmldbwdf.html

[S45] C++：lambda
来源：http://dali.pengpengdd.cyou/Article/details/gtnrxlhntt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yueranfly.top/Article/details/gtoffeogje.html

[S46] C++：函数模板
来源：http://dali.0kj1m.cn/Article/details/gtfueyhajo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuxming.cn/Article/details/gtfwstticd.html

[S47] C++：结构化绑定遍历
来源：http://dali.jlsjyb.cn/Article/details/gtquydvboo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolyuxlda.html

[S48] C++：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtzmrrrmpq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sxryk.cn/Article/details/gtqzuuelkq.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddljkvqd.html

[S49] C++：写文件
来源：http://dali.9152youxi.cn/Article/details/gthazyrndw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zycfv.cn/Article/details/gtutoiewtd.html

[S50] C++：格式化数字
来源：http://dali.ehwqpu.com/Article/details/gtywlrdens.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtjuwvevsc.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzfsicqp.html

static_cast<double>(a) / b
来源：http://dali.xziqi.cn/Article/details/gtqxhokmnn.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswmejipg.html

int size() const noexcept { return n_; }
来源：http://dali.daxiang520.top/Article/details/gttgwkrxid.html

[S53] C++：移动语义
来源：http://dali.yanxiufei.cn/Article/details/gtvkysjawo.html

std::vector<int> w = std::move(v);
来源：http://dali.xylfe.cn/Article/details/gtzncjzloj.html

[S54] C++：异常处理
来源：http://dali.tianlin.xyz/Article/details/gtnugevell.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinqigfzy.top/Article/details/gtgxmkfbkf.html

[S55] C++：结构化绑定
来源：http://dali.smart0.xyz/Article/details/gteszkktvm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shzxlz.cn/Article/details/gtfbpwqnuu.html

[S56] C++：optional
来源：http://dali.aibaodan.cn/Article/details/gtbmpsbcdk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.quarkkingdee.top/Article/details/gtcoffvwse.html

[S57] C++：编译期常量
来源：http://dali.hysaishi.cn/Article/details/gtnndsobrf.html

constexpr int N = 10;
来源：http://dali.sweek.top/Article/details/gtzjddtnhv.html

[S58] C++：命名空间
来源：http://dali.nwbrower.top/Article/details/gtnebmfaem.html

namespace ns { int f() { return 1; } }
来源：http://dali.shangyingyoupin.top/Article/details/gthyoklvlz.html

[S59] C++：静态断言
来源：http://dali.aizwys.cn/Article/details/gtysjoawqr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzqzceua.html

[S60] C++：遍历并删除元素
来源：http://dali.yonumen.top/Article/details/gtjtitkozk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yangfankeji.com/Article/details/gtvljvbjer.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtfswidugv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tian-w.cn/Article/details/gtzirurzxu.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtkotubhqg.html

[T01] Kotlin：Hello World
来源：http://dali.tanke756.top/Article/details/gtufqamfdj.html

println("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtskvicylf.html

[T02] Kotlin：变量
来源：http://dali.havefunace.top/Article/details/gtxyhzwlfq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.iojbl.cn/Article/details/gttlbtpshp.html

[T03] Kotlin：字符串模板
来源：http://dali.cheryme.top/Article/details/gtxmzihqli.html

"值: $b"
来源：http://dali.birdmap.top/Article/details/gtgjubyvdy.html

[T04] Kotlin：空安全
来源：http://dali.wangdashe.top/Article/details/gtfanjuntt.html

val n: String? = null;  n?.length
来源：http://dali.hysaishi.cn/Article/details/gttvuvelfd.html

[T05] Kotlin：when 表达式
来源：http://dali.daria6918.cn/Article/details/gtudlomlwc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.pycfn.com/Article/details/gtooyfkbhf.html

[T06] Kotlin：集合映射
来源：http://dali.gaohongyu789.top/Article/details/gtlwdaexmp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.haohaochexian.top/Article/details/gtbpkzelso.html

[T07] Kotlin：集合过滤
来源：http://dali.wangdashe.top/Article/details/gteburxmcn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jianghu66.top/Article/details/gtefqkeogi.html

[T08] Kotlin：数据类
来源：http://dali.gogol.net.cn/Article/details/gtayhtwwag.html

data class User(val name: String, val age: Int)
来源：http://dali.smart0.xyz/Article/details/gtuowujiwq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gtzfcvudhv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhengqikj.top/Article/details/gtquhiosmd.html

[T10] Kotlin：默认参数
来源：http://dali.hywenlv.cn/Article/details/gtpuefwwse.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jiagoushi.top/Article/details/gtyngeszwm.html

[T11] Kotlin：协程
来源：http://dali.hnxiangtu.top/Article/details/gtylakzlky.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhiwuduotai.top/Article/details/gtumsmznsp.html

[T12] Kotlin：解构声明
来源：http://dali.shuidangran.top/Article/details/gtfgrrwbka.html

val (a, b) = Pair(1, 2)
来源：http://dali.yonumen.top/Article/details/gtpiqtfdjp.html

[T13] Kotlin：只读 Map
来源：http://dali.nwbrower.top/Article/details/gtfeozpfqq.html

val m = mapOf("a" to 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtqzymvbcr.html

[T14] Kotlin：循环
来源：http://dali.gzhubu.top/Article/details/gtxxclfpvl.html

for (i in 1..10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gtpeccbhli.html


<!-- 参考信息 -->