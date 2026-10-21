代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sxryk.cn/Article/details/gtekubkwci.html

[R16] until 等待条件
来源：http://dali.jqgufenzy.top/Article/details/gtlkqdylly.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gtbozpyavz.html

[R17] 数组定义与取值
来源：http://dali.kuanghao11.cn/Article/details/gtoswddcos.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxinkj.top/Article/details/gtsbamxbgm.html

[R18] 遍历数组
来源：http://dali.dianchejie.cn/Article/details/gtiwvlnmtv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pycfn.com/Article/details/gtvhxzulcc.html

[R19] 数组长度
来源：http://dali.vqdsnc.cn/Article/details/gtrrxwcadw.html

echo "${#arr[@]}"
来源：http://dali.jqgfzy.top/Article/details/gtduaxytru.html

[R20] 关联数组（字典）
来源：http://dali.guannengcc.top/Article/details/gtxrzlogsr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgfzy.top/Article/details/gtbfescten.html

[R21] 字符串长度
来源：http://dali.tianlin.xyz/Article/details/gtvddfmnhb.html

echo "${#s}"
来源：http://dali.zhongyouzk.top/Article/details/gtfqombsyg.html

[R22] 截取子串
来源：http://dali.sweek.top/Article/details/gtdrfcuxdb.html

echo "${s:0:5}"
来源：http://dali.gzhubu.top/Article/details/gtwubivuph.html

[R23] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gtmxxhqwgz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yongpay.top/Article/details/gtswkqgdax.html

[R24] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gttnxvgeku.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigfzy.top/Article/details/gtuubxzswa.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkbjaybj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.birdmap.top/Article/details/gtrcstibwo.html

[R26] 命令替换
来源：http://dali.bjfxy.top/Article/details/gtkpoumobd.html

now=$(date +%F); echo "$now"
来源：http://dali.bjfxy.top/Article/details/gtrzuptwbj.html

[R27] 算术展开
来源：http://dali.shzxlz.cn/Article/details/gtzzauhmzk.html

echo $((1 + 2 * 3))
来源：http://dali.havefunace.top/Article/details/gtpshwzpzh.html

[R28] 浮点运算
来源：http://dali.sufxvd.cn/Article/details/gtfxwxtxqg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhongyouzk.top/Article/details/gtuexbxfaj.html

[R29] 定义函数
来源：http://dali.0kj1m.cn/Article/details/gtpkrzmpuo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tian-w.cn/Article/details/gtcmlzozng.html

[R30] 函数返回状态码
来源：http://dali.chenjidiqi.icu/Article/details/gtljekibhj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hywenlv.cn/Article/details/gtuvqyvfey.html

[R31] 局部变量
来源：http://dali.jiagoushi.top/Article/details/gtkgiwlbus.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnncmlnik.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjeirzwv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gtnsaoppli.html

[R33] 捕获错误并提示行号
来源：http://dali.zhiwuduotai.top/Article/details/gtakcojzdu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.smart0.xyz/Article/details/gtfzjsguqk.html

[R34] 退出时清理
来源：http://dali.yongpay.top/Article/details/gtdgppjjhq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangdashe.top/Article/details/gthabgczfd.html

[R35] 后台执行并等待
来源：http://dali.quarkkingdee.top/Article/details/gtwspfdgoj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.bjfxy.top/Article/details/gtdpqjmgpf.html

[R36] 并发执行多个任务
来源：http://dali.daxiang520.top/Article/details/gtsyjgzstu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangdashe.top/Article/details/gtggyxwxsm.html

[R37] 把输出赋给变量
来源：http://dali.hysaishi.cn/Article/details/gtvjxntavh.html

files=$(ls -1)
来源：http://dali.yj20258888.top/Article/details/gtzbrpkgld.html

[R38] 管道串联
来源：http://dali.cucudq.cn/Article/details/gtqwhnzbur.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgfzy.top/Article/details/gtfpigctul.html

[R39] 重定向标准输出与错误
来源：http://dali.hysaishi.cn/Article/details/gtaknrtngf.html

cmd > out.log 2>&1
来源：http://dali.chenlongwang.top/Article/details/gttruubmuo.html

[R40] 追加写日志
来源：http://dali.gotoacloud.top/Article/details/gtulkdlugs.html

echo "log" >> out.log
来源：http://dali.zhongyouzk.top/Article/details/gtgsnvqdir.html

[R41] 丢弃输出
来源：http://dali.hysaishi.cn/Article/details/gtndnyuukj.html

cmd >/dev/null 2>&1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjeigdspp.html

[R42] 输入重定向
来源：http://dali.dashuyun.cn/Article/details/gtaxympcok.html

wc -l < a.txt
来源：http://dali.tanke756.top/Article/details/gtdjvczcrb.html

[R43] 按名字查找文件
来源：http://dali.cqqwz.cn/Article/details/gtblhkypqi.html

find . -name "*.log" -type f
来源：http://dali.yanxiufei.cn/Article/details/gtnkifhzcx.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangtech.top/Article/details/gtabmonaov.html

find . -mtime -7 -type f
来源：http://dali.yangfankeji.com/Article/details/gtxwhyimmc.html

[R45] 批量删除
来源：http://dali.svipenyu.cn/Article/details/gtfutqkgpd.html

find . -name "*.tmp" -delete
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbbxvlub.html

[R46] 递归替换文件内容
来源：http://dali.fzhhl.top/Article/details/gtxvaezhqm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuetiantiany.cn/Article/details/gtriaipkbz.html

[R47] sed 单行替换
来源：http://dali.cucudq.cn/Article/details/gtstepdnhv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtmopelvhy.html

[R48] awk 取指定列
来源：http://dali.hywenlv.cn/Article/details/gtwdeetmqt.html

awk '{print $1, $3}' a.txt
来源：http://dali.redwolf501.top/Article/details/gtavyiqefg.html

[R49] awk 带条件
来源：http://dali.0kj1m.cn/Article/details/gtnbnlerdw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yangfankeji.com/Article/details/gtebajobfs.html

[R50] awk 求和
来源：http://dali.zdqjudy.top/Article/details/gtwrlbjlgk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtxbknoaat.html

[R51] 排序去重取前几
来源：http://dali.meibo888.top/Article/details/gttomrvvbv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ybcxt.top/Article/details/gtqutgrbce.html

[R52] 统计行数
来源：http://dali.hongshengwenyu.top/Article/details/gtyppyjnnt.html

wc -l a.txt
来源：http://dali.yj20258888.top/Article/details/gtbkkwpfnx.html

[R53] 查看文件头与实时尾
来源：http://dali.shzxlz.cn/Article/details/gthtbbcqhr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.fzhhl.top/Article/details/gtoczfiodi.html

[R54] 比较两个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtlguiwasz.html

diff a.txt b.txt
来源：http://dali.xziqi.cn/Article/details/gtlxcmccod.html

[R55] 压缩与解压
来源：http://dali.wangshuangyany.cn/Article/details/gtvjxovqqk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yongpay.top/Article/details/gtphizgzaf.html

[R56] 远程拷贝
来源：http://dali.zhoulong.xyz/Article/details/gtzpccvsbo.html

scp file user@host:/path/
来源：http://dali.kuanghao11.cn/Article/details/gtvwalgtjx.html

[R57] 远程执行命令
来源：http://dali.hnqzz.top/Article/details/gtohbvjcac.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgyrrjxn.html

[R58] 下载文件
来源：http://dali.hysaishi.cn/Article/details/gtjemsasmk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangshuangyany.cn/Article/details/gtitrthzdk.html

[R59] 发 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzchgfee.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ivvv.top/Article/details/gtgzvjhyhy.html

[R60] 只看 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gtkrogwxrf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xziqi.cn/Article/details/gtsljcuzim.html

[R61] 磁盘占用
来源：http://dali.zhoulong.xyz/Article/details/gteyhmcvtx.html

df -h;  du -sh *
来源：http://dali.haohaochexian.top/Article/details/gtalxggglk.html

[R62] 找最占空间的文件
来源：http://dali.jqgufenzy.top/Article/details/gtqclxtbik.html

du -ah . | sort -rh | head -10
来源：http://dali.sweek.top/Article/details/gtbyjzhxxy.html

[R63] 内存与进程
来源：http://dali.0kj1m.cn/Article/details/gtmxiatila.html

free -h;  ps aux | grep nginx
来源：http://dali.yongpay.top/Article/details/gtucmwunma.html

[R64] 结束进程
来源：http://dali.cdnleiting.top/Article/details/gteaoxmmke.html

kill -9 $(pgrep -f app.py)
来源：http://dali.kuanghao11.cn/Article/details/gtyhputlnv.html

[R65] 查看端口占用
来源：http://dali.jinqigufen.top/Article/details/gtuyysfqrb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ydzc1.top/Article/details/gtpyepjojk.html

[R66] 定时任务
来源：http://dali.nanxuanxn.top/Article/details/gtgupdbfty.html

crontab -e;  crontab -l
来源：http://dali.yj202588.top/Article/details/gtnszvicff.html

[R67] 生成随机十六进制串
来源：http://dali.jiagoushi.top/Article/details/gtakapxdfl.html

openssl rand -hex 16
来源：http://dali.yueranfly.top/Article/details/gthgurwpfj.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gtjfivivmr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.smart0.xyz/Article/details/gttqdijqkg.html

[R69] 生成随机密码
来源：http://dali.zhongyouzk.top/Article/details/gtacstrjyo.html

head -c 16 /dev/urandom | base64
来源：http://dali.316326.xyz/Article/details/gtpftcusxr.html

[R70] 时间戳与互转
来源：http://dali.cashguo.top/Article/details/gtarnrnufk.html

date +%s;  date -d @1700000000
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqxbulvz.html

[R71] 日期格式化
来源：http://dali.316326.xyz/Article/details/gtzeifsegs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yueranfly.top/Article/details/gtcpghaiue.html

[R72] 等待端口就绪
来源：http://dali.yuxming.cn/Article/details/gtjunddzju.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yueranfly.top/Article/details/gtxtxohitn.html

[R73] 分割大日志
来源：http://dali.tian-w.cn/Article/details/gthpstuxif.html

split -l 1000 big.log part_
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjubibhb.html

[R74] 批量重命名
来源：http://dali.zhengqikj.top/Article/details/gtccmaghel.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtriouqj.html

[R75] 导出环境变量
来源：http://dali.yueranfly.top/Article/details/gtcmkgzjes.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.svipenyu.cn/Article/details/gtjyeukmjh.html

[R76] 使用临时文件
来源：http://dali.hysaishi.cn/Article/details/gtwmmvroou.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gttxtusuos.html

[R77] 读取用户输入
来源：http://dali.cucudq.cn/Article/details/gtwvwruosx.html

read -rp "请输入: " ans
来源：http://dali.316326.xyz/Article/details/gtczartsvu.html

[R78] 交互式菜单
来源：http://dali.yj20258888.top/Article/details/gtalzgohyh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258888.top/Article/details/gtdnqpumbx.html

[R79] 解析命令行选项
来源：http://dali.xuanzx.com/Article/details/gtukwhecjf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuanzhike.top/Article/details/gtgdmuehpu.html

[R80] 查看脚本执行耗时
来源：http://dali.gaohongyu789.top/Article/details/gttouiiubq.html

time ./run.sh
来源：http://dali.quarkkingdee.top/Article/details/gtocjarlxp.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtchmeoauk.html

S. C / C++ 专题
来源：http://dali.sweek.top/Article/details/gtpvgikdcw.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtjopingfb.html

[S01] C：Hello World
来源：http://dali.yongpay.top/Article/details/gtvmyndhfb.html

#include <stdio.h>
来源：http://dali.redwolf501.top/Article/details/gtmlpszhgo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.svipenyu.cn/Article/details/gtxzmuocbz.html

[S02] C：变量与格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gtvrlwpufw.html

int a = 10; printf("%d\n", a);
来源：http://dali.aibaodan.cn/Article/details/gtecmafyot.html

[S03] C：读入整数
来源：http://dali.mhx1999.top/Article/details/gtwmwpmfcq.html

int x; scanf("%d", &x);
来源：http://dali.mhx1999.top/Article/details/gtsxbjrqvk.html

[S04] C：字符串复制
来源：http://dali.vqdsnc.cn/Article/details/gtrkfgdgpw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ppjwa.cn/Article/details/gtfshpwpbf.html

[S05] C：字符串长度
来源：http://dali.zhixingplan.top/Article/details/gtxwlmspfm.html

strlen(s)
来源：http://dali.guannengcc.top/Article/details/gtaeeqqxyt.html

[S06] C：字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gtafkwvydb.html

strcmp(a, b) == 0
来源：http://dali.vqdsnc.cn/Article/details/gtieepnibu.html

[S07] C：数组遍历求和
来源：http://dali.daxiang520.top/Article/details/gtbelirmrj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ppjwa.cn/Article/details/gttvzgirmd.html

[S08] C：动态内存分配与释放
来源：http://dali.sufxvd.cn/Article/details/gtkzeeobby.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxuanxn.top/Article/details/gtxdyugxgg.html

[S09] C：结构体定义与初始化
来源：http://dali.tianlin.xyz/Article/details/gtnoesekbw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqpldjxdv.html

[S10] C：指针与解引用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturjvlamd.html

int *p = &a;  *p = 5;
来源：http://dali.zhixingplan.top/Article/details/gtnkhvdjce.html

[S11] C：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtsmmbubux.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sysykeji.top/Article/details/gtgumxywpz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sufxvd.cn/Article/details/gtkfloeyep.html

fclose(f);
来源：http://dali.cheryme.top/Article/details/gtrgtrurzk.html

[S12] C：写文件
来源：http://dali.gzhubu.top/Article/details/gtkgjocjmz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gtejoybjbp.html

[S13] C：宏定义
来源：http://dali.sweek.top/Article/details/gtbherxxxb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhoulong.xyz/Article/details/gtqlhdxxud.html

[S14] C：枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtncivtsij.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinqigufen.top/Article/details/gtdtezkoll.html

[S15] C：类型转换
来源：http://dali.aibaodan.cn/Article/details/gtsuqizcrw.html

(double) a / b
来源：http://dali.birdmap.top/Article/details/gtvnduccvn.html

[S16] C：位操作置位
来源：http://dali.daxiang520.top/Article/details/gtrbfoxkhj.html

x |= (1 << 3);
来源：http://dali.sxryk.cn/Article/details/gtlmusoixx.html

[S17] C：安全拼接字符串
来源：http://dali.fzhhl.top/Article/details/gtnpdbxoxp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgufenzy.top/Article/details/gtrbqlxcca.html

[S18] C：命令行参数
来源：http://dali.iojbl.cn/Article/details/gtbstwurbg.html

int main(int argc, char **argv)
来源：http://dali.snrcjt.cn/Article/details/gtfhyycbjh.html

[S19] C：快速排序
来源：http://dali.316326.xyz/Article/details/gtruldrhit.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gtlojbwjfc.html

[S20] C：二分查找
来源：http://dali.smart0.xyz/Article/details/gtijmwrusb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gtoiaevofi.html

[S21] C：字符类别判断
来源：http://dali.jinqigufen.top/Article/details/gtgmwpsrtz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daria6918.cn/Article/details/gtywormncm.html

[S22] C：字符串转数字
来源：http://dali.zhengqikj.top/Article/details/gtrucedjnr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.9152youxi.cn/Article/details/gtrmkkptob.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gtcxfgqdac.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yangfankeji.com/Article/details/gttmzgxgwv.html

[S24] C：获取本地时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkokdwpql.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pycfn.com/Article/details/gtoghqxzvo.html

[S25] C：内存拷贝
来源：http://dali.jianghu66.top/Article/details/gtfllpswgh.html

memcpy(dst, src, n);
来源：http://dali.tanke756.top/Article/details/gthfiusfnt.html

[S26] C：内存清零
来源：http://dali.jqgfzy.top/Article/details/gtdmwqezzi.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gtghqafket.html

[S27] C：定义常量
来源：http://dali.ivvv.top/Article/details/gtluuuhnsd.html

const double PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gtlynlzdsi.html

[S28] C：静态变量
来源：http://dali.hongshengwenyu.top/Article/details/gtwrbphpdh.html

static int counter = 0;
来源：http://dali.jiagoushi.top/Article/details/gtkolkihwb.html

[S29] C：变参函数
来源：http://dali.hongshengwenyu.top/Article/details/gteslrvywr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258.top/Article/details/gtpysarjoh.html

[S30] C：头文件保护
来源：http://dali.hfpthk.cn/Article/details/gtdakneefd.html

#ifndef X_H
来源：http://dali.wangshuangyany.cn/Article/details/gtohgtoaoi.html

#define X_H
来源：http://dali.chenjidiqi.icu/Article/details/gtlrmpozys.html

#endif
来源：http://dali.nanxuanxn.top/Article/details/gtohpbqwtn.html

[S31] C++：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtofhubmkp.html

#include <iostream>
来源：http://dali.316326.xyz/Article/details/gtafeizovj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigufen.top/Article/details/gtboyvhhea.html

[S32] C++：字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtudfjgyvd.html

std::string s = "hi";  s += "!";
来源：http://dali.cqqwz.cn/Article/details/gtuplgwylf.html

[S33] C++：vector 增删
来源：http://dali.daxiang520.top/Article/details/gtvnmnetpk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.c1oappe.top/Article/details/gtsshmuddo.html

[S34] C++：遍历 vector
来源：http://dali.andypj.xyz/Article/details/gtdqrfusqc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sxryk.cn/Article/details/gtcksclkty.html

[S35] C++：map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmoevsux.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtwttieyje.html

[S36] C++：unordered_map
来源：http://dali.fzhhl.top/Article/details/gtbtlsahdd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtefaltgax.html

[S37] C++：set
来源：http://dali.zhongyouzk.top/Article/details/gtbhdpqsef.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gogol.net.cn/Article/details/gtjulsxeic.html

[S38] C++：排序
来源：http://dali.hammf.cn/Article/details/gtdnbgfozg.html

std::sort(v.begin(), v.end());
来源：http://dali.meibo888.top/Article/details/gtytgwewwk.html

[S39] C++：自定义比较器排序
来源：http://dali.nwbrower.top/Article/details/gtcydlmivk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.pycfn.com/Article/details/gtlqjvviop.html

[S40] C++：查找元素
来源：http://dali.smart0.xyz/Article/details/gtcxuqtxir.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.redwolf501.top/Article/details/gtblzvanij.html

[S41] C++：类与构造函数
来源：http://dali.svipenyu.cn/Article/details/gtwywqiplo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sweek.top/Article/details/gtwztqoayp.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigufen.top/Article/details/gtigzjomes.html

class B : public Base { public: void f() override {} };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthyhsvwqz.html

[S43] C++：智能指针
来源：http://dali.vqdsnc.cn/Article/details/gtddroiayd.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgfzy.top/Article/details/gtpqpzhiqb.html

[S44] C++：引用传参
来源：http://dali.yj20258.top/Article/details/gthklpemxs.html

void inc(int &x) { ++x; }
来源：http://dali.zhoulong.xyz/Article/details/gtvujosecs.html

[S45] C++：lambda
来源：http://dali.nanxinkj.top/Article/details/gtiksmtdba.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.vqdsnc.cn/Article/details/gtfghdwqzs.html

[S46] C++：函数模板
来源：http://dali.jinghuilouyu.cn/Article/details/gtqydcxqxc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tanke756.top/Article/details/gtluqlklxs.html

[S47] C++：结构化绑定遍历
来源：http://dali.nanxinkj.top/Article/details/gtngywllxy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zdqjudy.top/Article/details/gtpejqfflc.html

[S48] C++：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtyjebqwta.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.meibo888.top/Article/details/gtmsxrzvju.html

while (std::getline(in, line)) { }
来源：http://dali.cashguo.top/Article/details/gtmydicwzs.html

[S49] C++：写文件
来源：http://dali.andypj.xyz/Article/details/gteatwrfic.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyadltqvk.html

[S50] C++：格式化数字
来源：http://dali.gzhubu.top/Article/details/gtyjpxyxjn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtxsaphwlj.html

[S51] C++：显式类型转换
来源：http://dali.chenjidiqi.icu/Article/details/gtachwydqd.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstwdncbl.html

[S52] C++：const 与 noexcept
来源：http://dali.zhoulong.xyz/Article/details/gtqdoxiitj.html

int size() const noexcept { return n_; }
来源：http://dali.sufxvd.cn/Article/details/gtntioxpki.html

[S53] C++：移动语义
来源：http://dali.sufxvd.cn/Article/details/gttlicctrl.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqaixswhy.html

[S54] C++：异常处理
来源：http://dali.hnqzz.top/Article/details/gtynolleyo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yanxiufei.cn/Article/details/gtarpyglyk.html

[S55] C++：结构化绑定
来源：http://dali.shangyingyoupin.top/Article/details/gtilhqzogj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hfpthk.cn/Article/details/gtnvhhnrgl.html

[S56] C++：optional
来源：http://dali.andypj.xyz/Article/details/gtrshwmxnb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yvedp.cn/Article/details/gtgivdgkoj.html

[S57] C++：编译期常量
来源：http://dali.jinghuilouyu.cn/Article/details/gtotavexjk.html

constexpr int N = 10;
来源：http://dali.havefunace.top/Article/details/gtqxqpfcqb.html

[S58] C++：命名空间
来源：http://dali.kuanghao11.cn/Article/details/gtsabbotgg.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtzqlqhsfe.html

[S59] C++：静态断言
来源：http://dali.jiagoushi.top/Article/details/gtdessaobs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangshuangyany.cn/Article/details/gtfkfbstey.html

[S60] C++：遍历并删除元素
来源：http://dali.kuanghao11.cn/Article/details/gtxxcfvast.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jiagoushi.top/Article/details/gtughrnufe.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtvmnflitw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhoulong.xyz/Article/details/gtgzflnmcj.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtjveighrg.html

[T01] Kotlin：Hello World
来源：http://dali.cashguo.top/Article/details/gtlulrwsxz.html

println("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gtonwfiarn.html

[T02] Kotlin：变量
来源：http://dali.gaohongyu789.top/Article/details/gtigwyelvl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj202588.top/Article/details/gtdrlzcoey.html

[T03] Kotlin：字符串模板
来源：http://dali.gzhubu.top/Article/details/gttozfcayt.html

"值: $b"
来源：http://dali.sxryk.cn/Article/details/gtahuwkwqz.html

[T04] Kotlin：空安全
来源：http://dali.fzhhl.top/Article/details/gtccgpklxc.html

val n: String? = null;  n?.length
来源：http://dali.cdnleiting.top/Article/details/gtgcnxcoaz.html

[T05] Kotlin：when 表达式
来源：http://dali.havefunace.top/Article/details/gtsavdlipl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gaohongyu789.top/Article/details/gtgxhrlmqs.html

[T06] Kotlin：集合映射
来源：http://dali.aizwys.cn/Article/details/gtjjuheutx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.redwolf501.top/Article/details/gtfgqavtwe.html

[T07] Kotlin：集合过滤
来源：http://dali.yangfankeji.com/Article/details/gtszvjsehj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aibaodan.cn/Article/details/gttmduytwj.html

[T08] Kotlin：数据类
来源：http://dali.birdmap.top/Article/details/gtyhcbgvvh.html

data class User(val name: String, val age: Int)
来源：http://dali.daxiang520.top/Article/details/gtukqnpvqt.html

[T09] Kotlin：扩展函数
来源：http://dali.quarkkingdee.top/Article/details/gtahkricyp.html

fun String.exclaim() = this + "!"
来源：http://dali.mhx1999.top/Article/details/gtodpvfwbf.html

[T10] Kotlin：默认参数
来源：http://dali.cheryme.top/Article/details/gtmmmgklbr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tianlin.xyz/Article/details/gtciivsgma.html

[T11] Kotlin：协程
来源：http://dali.snrcjt.cn/Article/details/gtylvyzyky.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daria6918.cn/Article/details/gtmujltrdc.html

[T12] Kotlin：解构声明
来源：http://dali.pengpengdd.cyou/Article/details/gtkdwcycmp.html

val (a, b) = Pair(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gtwiklqtgg.html

[T13] Kotlin：只读 Map
来源：http://dali.cqqwz.cn/Article/details/gtbxjcvojc.html

val m = mapOf("a" to 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtomlunozp.html

[T14] Kotlin：循环
来源：http://dali.yonumen.top/Article/details/gtwlctniuq.html

for (i in 1..10) println(i)
来源：http://dali.yongpay.top/Article/details/gtlgjcwnrv.html

[T15] Kotlin：接口
来源：http://dali.quarkkingdee.top/Article/details/gtovhuzikj.html

interface Shape { fun area(): Double }
来源：http://dali.wangdashe.top/Article/details/gtgpsvxmyb.html

[T16] Swift：Hello World
来源：http://dali.bjfxy.top/Article/details/gtjfoaeife.html

print("Hello")
来源：http://dali.hammf.cn/Article/details/gtdtofxqmo.html

[T17] Swift：变量与常量
来源：http://dali.hnxiangtu.top/Article/details/gtctispeep.html

var a = 1;  let b = 2
来源：http://dali.yonumen.top/Article/details/gtipjhcder.html

[T18] Swift：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnecqaxha.html

"值: \(b)"
来源：http://dali.pycfn.com/Article/details/gteiohhsmr.html


<!-- 参考信息 -->