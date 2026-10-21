代发 wailian999

name="${1:-default}"
来源：http://dali.cucudq.cn/Article/details/gtmuomwdiz.html

[R06] 判断命令是否存在
来源：http://dali.chenlongwang.top/Article/details/gtwtdjrqmh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtkjbucmdu.html

[R07] if 判断文件
来源：http://dali.tian-w.cn/Article/details/gtqvzwhltl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.guannengcc.top/Article/details/gtinakkrxe.html

[R08] 数值比较
来源：http://dali.ybcxt.top/Article/details/gtzelsscxl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.aizwys.cn/Article/details/gtrotgssfy.html

[R09] 字符串比较
来源：http://dali.zycfv.cn/Article/details/gtbxrhzgco.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jyoumei.cn/Article/details/gtkjywsfyy.html

[R10] 正则匹配
来源：http://dali.zhengqikj.top/Article/details/gtsjlnpxra.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shuidangran.top/Article/details/gtlmqleeyz.html

[R11] case 多分支
来源：http://dali.316326.xyz/Article/details/gtcuxnnivq.html

case "$1" in
来源：http://dali.cqqwz.cn/Article/details/gtvdbyboti.html

start) echo "启动" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtgvzvjjov.html

stop)  echo "停止" ;;
来源：http://dali.jqgufenzy.top/Article/details/gtzbkpckpz.html

*)     echo "未知命令" ;;
来源：http://dali.guowangkeji.top/Article/details/gtughgeafm.html

esac
来源：http://dali.tianlin.xyz/Article/details/gtndwxhkci.html

[R12] for 遍历文件
来源：http://dali.zycfv.cn/Article/details/gthrstdgsg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhiwuduotai.top/Article/details/gthofsteip.html

[R13] for 计数循环
来源：http://dali.dianchejie.cn/Article/details/gtjuhtxphi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gtulvjfpwk.html

[R14] C 风格 for
来源：http://dali.gogol.net.cn/Article/details/gtsopeffnp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.svipenyu.cn/Article/details/gtqksrliph.html

[R15] while 逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtyushdlgi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigufen.top/Article/details/gtadoacgbw.html

[R16] until 等待条件
来源：http://dali.guowangkeji.top/Article/details/gtpbvmrvxd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj202588.top/Article/details/gtoeujffhg.html

[R17] 数组定义与取值
来源：http://dali.fzhhl.top/Article/details/gthbbgktno.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hammf.cn/Article/details/gtecruhneu.html

[R18] 遍历数组
来源：http://dali.fzhhl.top/Article/details/gtkifnqfgx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aibaodan.cn/Article/details/gthkhkyywz.html

[R19] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gtjczbtwyx.html

echo "${#arr[@]}"
来源：http://dali.316326.xyz/Article/details/gtcfphfodx.html

[R20] 关联数组（字典）
来源：http://dali.tian-w.cn/Article/details/gtbigucqrt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hywenlv.cn/Article/details/gtabxyteeu.html

[R21] 字符串长度
来源：http://dali.shzxlz.cn/Article/details/gtwwkgrwhx.html

echo "${#s}"
来源：http://dali.pycfn.com/Article/details/gtbugrlhfj.html

[R22] 截取子串
来源：http://dali.dashuyun.cn/Article/details/gtupvqkupz.html

echo "${s:0:5}"
来源：http://dali.fzhhl.top/Article/details/gtibwxlbci.html

[R23] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gtyugndgte.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shzxlz.cn/Article/details/gtljaqsteb.html

[R24] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gtcmqeduap.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hammf.cn/Article/details/gtmukmajfb.html

[R25] 去后缀 / 去前缀
来源：http://dali.daxiang520.top/Article/details/gtiyecfigz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dashuyun.cn/Article/details/gtnldamojc.html

[R26] 命令替换
来源：http://dali.guannengcc.top/Article/details/gtczqsqtrh.html

now=$(date +%F); echo "$now"
来源：http://dali.yuxming.cn/Article/details/gtdgghsibn.html

[R27] 算术展开
来源：http://dali.jinqigufen.top/Article/details/gtmfapobve.html

echo $((1 + 2 * 3))
来源：http://dali.nanxinkj.top/Article/details/gtjmnlnzgp.html

[R28] 浮点运算
来源：http://dali.smart0.xyz/Article/details/gtjjkwswal.html

echo "scale=2; 10/3" | bc
来源：http://dali.snrcjt.cn/Article/details/gteteynupv.html

[R29] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gtzdwwvtqt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.meibo888.top/Article/details/gtkamnitmq.html

[R30] 函数返回状态码
来源：http://dali.zhengqikj.top/Article/details/gtxdpdgqfk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jiagoushi.top/Article/details/gtpyvqeqyk.html

[R31] 局部变量
来源：http://dali.fengsongda.top/Article/details/gtzhnkaiho.html

f() { local x=1; echo "$x"; }
来源：http://dali.cheryme.top/Article/details/gthnhiaozw.html

[R32] 参数个数校验
来源：http://dali.tianlin.xyz/Article/details/gtolwmjmjo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpubccytl.html

[R33] 捕获错误并提示行号
来源：http://dali.zhixingplan.top/Article/details/gtzmmzppwx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.meibo888.top/Article/details/gtiwiebvea.html

[R34] 退出时清理
来源：http://dali.ydzc1.top/Article/details/gtocifdnzv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sxryk.cn/Article/details/gtvmgwfvpv.html

[R35] 后台执行并等待
来源：http://dali.sufxvd.cn/Article/details/gtnuiumefq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhongyouzk.top/Article/details/gtedvyijjh.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangtech.top/Article/details/gtcqeusuep.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhoulong.xyz/Article/details/gtnawxofic.html

[R37] 把输出赋给变量
来源：http://dali.jinqigufen.top/Article/details/gtccdjulhd.html

files=$(ls -1)
来源：http://dali.dianchejie.cn/Article/details/gtzbztvnmr.html

[R38] 管道串联
来源：http://dali.quarkkingdee.top/Article/details/gtzpxwchoq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xuanzx.com/Article/details/gtgewnxuyo.html

[R39] 重定向标准输出与错误
来源：http://dali.xinyue.icu/Article/details/gtdyqbslys.html

cmd > out.log 2>&1
来源：http://dali.cashguo.top/Article/details/gtnsmxnnpd.html

[R40] 追加写日志
来源：http://dali.vqdsnc.cn/Article/details/gtpyqndntw.html

echo "log" >> out.log
来源：http://dali.aibaodan.cn/Article/details/gtwmneglaj.html

[R41] 丢弃输出
来源：http://dali.jinqigufen.top/Article/details/gtnhxqfkdr.html

cmd >/dev/null 2>&1
来源：http://dali.bjfxy.top/Article/details/gtmkleliou.html

[R42] 输入重定向
来源：http://dali.yonumen.top/Article/details/gtecnnshux.html

wc -l < a.txt
来源：http://dali.zdqjudy.top/Article/details/gteknegrwc.html

[R43] 按名字查找文件
来源：http://dali.feifeiyinyue.top/Article/details/gtdyhptxhr.html

find . -name "*.log" -type f
来源：http://dali.daxiang520.top/Article/details/gtofzcspvz.html

[R44] 按修改时间查找
来源：http://dali.316326.xyz/Article/details/gtbbmzqjrn.html

find . -mtime -7 -type f
来源：http://dali.chenjidiqi.icu/Article/details/gtybvqrzko.html

[R45] 批量删除
来源：http://dali.chenzaomai.com/Article/details/gtrbxiwxxg.html

find . -name "*.tmp" -delete
来源：http://dali.gogol.net.cn/Article/details/gtpavcbvwx.html

[R46] 递归替换文件内容
来源：http://dali.wangdashe.top/Article/details/gtaeipcmhw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.meibo888.top/Article/details/gtpdqovbtw.html

[R47] sed 单行替换
来源：http://dali.ydzc1.top/Article/details/gtyhicyeob.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtjouapipx.html

[R48] awk 取指定列
来源：http://dali.fengsongda.top/Article/details/gtordehwgy.html

awk '{print $1, $3}' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtoqgsuzld.html

[R49] awk 带条件
来源：http://dali.sweek.top/Article/details/gtuiuvejie.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.mhx1999.top/Article/details/gtrbioarsu.html

[R50] awk 求和
来源：http://dali.sufxvd.cn/Article/details/gtoremuqfn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenlongwang.top/Article/details/gtrsbawpxp.html

[R51] 排序去重取前几
来源：http://dali.jqgfzy.top/Article/details/gtvemlmkoz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pycfn.com/Article/details/gtelqlkdnn.html

[R52] 统计行数
来源：http://dali.yanxiufei.cn/Article/details/gtzezdbzcl.html

wc -l a.txt
来源：http://dali.gogol.net.cn/Article/details/gtcpnkcttj.html

[R53] 查看文件头与实时尾
来源：http://dali.jlsjyb.cn/Article/details/gtbbtiwdga.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthplbkjcd.html

[R54] 比较两个文件
来源：http://dali.9152youxi.cn/Article/details/gtfrhqzhfl.html

diff a.txt b.txt
来源：http://dali.yuanzhike.top/Article/details/gtwtvarzbd.html

[R55] 压缩与解压
来源：http://dali.hammf.cn/Article/details/gtpourydno.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yonumen.top/Article/details/gtlrlmeqjh.html

[R56] 远程拷贝
来源：http://dali.snrcjt.cn/Article/details/gtortvojjy.html

scp file user@host:/path/
来源：http://dali.feifeiyinyue.top/Article/details/gtyumgfrlv.html

[R57] 远程执行命令
来源：http://dali.sufxvd.cn/Article/details/gtnncxzwcj.html

ssh user@host 'uptime'
来源：http://dali.kuanghao11.cn/Article/details/gtjduuirff.html

[R58] 下载文件
来源：http://dali.jiagoushi.top/Article/details/gtpdnatccm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shuidangran.top/Article/details/gtpktynzgy.html

[R59] 发 POST JSON
来源：http://dali.yonumen.top/Article/details/gtmboxumga.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tian-w.cn/Article/details/gtaojhfqgz.html

[R60] 只看 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gtrarwlrbj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sxryk.cn/Article/details/gtsunwyqpl.html

[R61] 磁盘占用
来源：http://dali.dianchejie.cn/Article/details/gtmgzvletc.html

df -h;  du -sh *
来源：http://dali.jqgufenzy.top/Article/details/gtzcweqdji.html

[R62] 找最占空间的文件
来源：http://dali.dianchejie.cn/Article/details/gtywzurwkh.html

du -ah . | sort -rh | head -10
来源：http://dali.vqdsnc.cn/Article/details/gtkifjkagv.html

[R63] 内存与进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvewyoqx.html

free -h;  ps aux | grep nginx
来源：http://dali.pycfn.com/Article/details/gtiwavxocm.html

[R64] 结束进程
来源：http://dali.guannengcc.top/Article/details/gtagarnxwv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sweek.top/Article/details/gtuolakfce.html

[R65] 查看端口占用
来源：http://dali.yanxiufei.cn/Article/details/gtvfnefljz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgfzy.top/Article/details/gtyfovchcb.html

[R66] 定时任务
来源：http://dali.yueranfly.top/Article/details/gtkhoqmvoi.html

crontab -e;  crontab -l
来源：http://dali.ivvv.top/Article/details/gtdsnbeuzl.html

[R67] 生成随机十六进制串
来源：http://dali.hywenlv.cn/Article/details/gtayoznamk.html

openssl rand -hex 16
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkbmlbmw.html

[R68] 计算文件校验值
来源：http://dali.smart0.xyz/Article/details/gtfwthvofb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gotoacloud.top/Article/details/gtzfnhtgks.html

[R69] 生成随机密码
来源：http://dali.xylfe.cn/Article/details/gtjxkidyov.html

head -c 16 /dev/urandom | base64
来源：http://dali.shangyingyoupin.top/Article/details/gtgrlpimsp.html

[R70] 时间戳与互转
来源：http://dali.zhengqikj.top/Article/details/gtupbwbikg.html

date +%s;  date -d @1700000000
来源：http://dali.ehwqpu.com/Article/details/gtigvtexrp.html

[R71] 日期格式化
来源：http://dali.hammf.cn/Article/details/gthnhxczlb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dashuyun.cn/Article/details/gtguwyrufj.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gteiqaklcm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gtsovvcvqj.html

[R73] 分割大日志
来源：http://dali.hysaishi.cn/Article/details/gtulvxloyt.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgsahwvoi.html

[R74] 批量重命名
来源：http://dali.shangyingyoupin.top/Article/details/gtpobxiggn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjddxbpgg.html

[R75] 导出环境变量
来源：http://dali.aibaodan.cn/Article/details/gtsrmrxwrw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zdqjudy.top/Article/details/gtzegjhzmq.html

[R76] 使用临时文件
来源：http://dali.zhiwuduotai.top/Article/details/gtswynmpuk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gthaycmpqz.html

[R77] 读取用户输入
来源：http://dali.andypj.xyz/Article/details/gtvvedmmzr.html

read -rp "请输入: " ans
来源：http://dali.mhx1999.top/Article/details/gtwopfehxy.html

[R78] 交互式菜单
来源：http://dali.yj202588.top/Article/details/gthalrzbpf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yongpay.top/Article/details/gtygrmdlmh.html

[R79] 解析命令行选项
来源：http://dali.hongshengwenyu.top/Article/details/gtwygtpkee.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.316326.xyz/Article/details/gthkpjomsm.html

[R80] 查看脚本执行耗时
来源：http://dali.sweek.top/Article/details/gtrkdjnvve.html

time ./run.sh
来源：http://dali.cucudq.cn/Article/details/gtitwfnjbx.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtsaesnjfb.html

S. C / C++ 专题
来源：http://dali.jinqigufen.top/Article/details/gtbjhglyai.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtuafgrsoh.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gtypgvitqf.html

#include <stdio.h>
来源：http://dali.birdmap.top/Article/details/gtsczmdszk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zdqjudy.top/Article/details/gtifwihxnz.html

[S02] C：变量与格式化输出
来源：http://dali.bjfxy.top/Article/details/gtkpeyjomd.html

int a = 10; printf("%d\n", a);
来源：http://dali.yonumen.top/Article/details/gtkibbrhfj.html

[S03] C：读入整数
来源：http://dali.andypj.xyz/Article/details/gtbfrvkoot.html

int x; scanf("%d", &x);
来源：http://dali.wangdashe.top/Article/details/gttoxgjkgs.html

[S04] C：字符串复制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohcvnakw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xinyue.icu/Article/details/gtpclnlxky.html

[S05] C：字符串长度
来源：http://dali.yvedp.cn/Article/details/gtjwhtklzf.html

strlen(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpylmxnpy.html

[S06] C：字符串比较
来源：http://dali.jiagoushi.top/Article/details/gthddeglid.html

strcmp(a, b) == 0
来源：http://dali.ybcxt.top/Article/details/gtqyykxzcf.html

[S07] C：数组遍历求和
来源：http://dali.svipenyu.cn/Article/details/gtrwjwwmsg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.0kj1m.cn/Article/details/gtxlnyaxgu.html

[S08] C：动态内存分配与释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkmqqzsx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hfpthk.cn/Article/details/gtcirinvks.html

[S09] C：结构体定义与初始化
来源：http://dali.pengpengdd.cyou/Article/details/gtdtbqxodl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gaohongyu789.top/Article/details/gtssiuwnzm.html

[S10] C：指针与解引用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtststcnuw.html

int *p = &a;  *p = 5;
来源：http://dali.c1oappe.top/Article/details/gtmgljeawo.html

[S11] C：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gthhmxcwun.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjbtwtdp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.daria6918.cn/Article/details/gtsoskevkl.html

fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gtwjopaqit.html

[S12] C：写文件
来源：http://dali.ybcxt.top/Article/details/gtdfvxshcr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.c1oappe.top/Article/details/gtaizplcta.html

[S13] C：宏定义
来源：http://dali.zdqjudy.top/Article/details/gtkuxlwpik.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhsonbun.html

[S14] C：枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoviyhlts.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangdashe.top/Article/details/gtxigcqknl.html

[S15] C：类型转换
来源：http://dali.haohaochexian.top/Article/details/gterlpqtas.html

(double) a / b
来源：http://dali.hnxiangtu.top/Article/details/gtneictcrc.html

[S16] C：位操作置位
来源：http://dali.fzhhl.top/Article/details/gtskrgamdt.html

x |= (1 << 3);
来源：http://dali.zdqjudy.top/Article/details/gtrwisrhpc.html

[S17] C：安全拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtffmyqium.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.316326.xyz/Article/details/gtqtbpnatk.html

[S18] C：命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gtgbyydjzt.html

int main(int argc, char **argv)
来源：http://dali.yvedp.cn/Article/details/gtoskctmpe.html

[S19] C：快速排序
来源：http://dali.yj202588.top/Article/details/gtzdxiegue.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ehwqpu.com/Article/details/gtvavxkomg.html

[S20] C：二分查找
来源：http://dali.ppjwa.cn/Article/details/gtnnjoecsi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gtnkaeasbr.html

[S21] C：字符类别判断
来源：http://dali.zhiwuduotai.top/Article/details/gtaovghnfb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhoulong.xyz/Article/details/gtuivriegp.html

[S22] C：字符串转数字
来源：http://dali.yuxming.cn/Article/details/gtluevqxmt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.redwolf501.top/Article/details/gtopjohmub.html

[S23] C：随机数
来源：http://dali.dashuyun.cn/Article/details/gtkfptjezb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dianchejie.cn/Article/details/gteygejgoy.html

[S24] C：获取本地时间
来源：http://dali.yangfankeji.com/Article/details/gtmzdtjlki.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dashuyun.cn/Article/details/gtjkhhgene.html

[S25] C：内存拷贝
来源：http://dali.jqgufenzy.top/Article/details/gtnxjqhqig.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhejbyvj.html

[S26] C：内存清零
来源：http://dali.iojbl.cn/Article/details/gtubhbfqeq.html

memset(a, 0, sizeof a);
来源：http://dali.chenjidiqi.icu/Article/details/gtkydtfrzj.html

[S27] C：定义常量
来源：http://dali.sufxvd.cn/Article/details/gtsovnxzfo.html

const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtjlgibelz.html

[S28] C：静态变量
来源：http://dali.jinqigfzy.top/Article/details/gtczatdpaj.html

static int counter = 0;
来源：http://dali.aizwys.cn/Article/details/gtdotpbubc.html

[S29] C：变参函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbznmytgp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gtgbcbofgp.html

[S30] C：头文件保护
来源：http://dali.pengpengdd.cyou/Article/details/gtncdsqcpr.html

#ifndef X_H
来源：http://dali.zhoulong.xyz/Article/details/gtjqksqyog.html

#define X_H
来源：http://dali.zhixingplan.top/Article/details/gtaozwttnh.html

#endif
来源：http://dali.mhx1999.top/Article/details/gthfkwwjwv.html

[S31] C++：Hello World
来源：http://dali.xziqi.cn/Article/details/gtlaacsakk.html

#include <iostream>
来源：http://dali.daxiang520.top/Article/details/gtdqzkjkji.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hfpthk.cn/Article/details/gtmwyjnvkl.html

[S32] C++：字符串
来源：http://dali.ydzc1.top/Article/details/gtglydnjog.html

std::string s = "hi";  s += "!";
来源：http://dali.aibaodan.cn/Article/details/gtiotoopbc.html

[S33] C++：vector 增删
来源：http://dali.gogol.net.cn/Article/details/gttevxapxm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hywenlv.cn/Article/details/gtkcrsgmib.html

[S34] C++：遍历 vector
来源：http://dali.jqgfzy.top/Article/details/gtxbjaoyzs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shzxlz.cn/Article/details/gtmkvjkuio.html

[S35] C++：map
来源：http://dali.pycfn.com/Article/details/gtvuupukby.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daxiang520.top/Article/details/gttclfogyr.html

[S36] C++：unordered_map
来源：http://dali.jiagoushi.top/Article/details/gtrdmrdifp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gtfozuujgg.html

[S37] C++：set
来源：http://dali.wangshuangyany.cn/Article/details/gtwwdezkun.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.dianchejie.cn/Article/details/gttoxzrdkv.html

[S38] C++：排序
来源：http://dali.fzhhl.top/Article/details/gtyqigrobr.html

std::sort(v.begin(), v.end());
来源：http://dali.ydzc1.top/Article/details/gtztplppfg.html

[S39] C++：自定义比较器排序
来源：http://dali.andypj.xyz/Article/details/gtyinsqcqi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hammf.cn/Article/details/gtqfyegofk.html

[S40] C++：查找元素
来源：http://dali.kuanghao11.cn/Article/details/gtqnalknst.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.redwolf501.top/Article/details/gtsxxdqhfq.html

[S41] C++：类与构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxltrmxyf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlmwzvce.html

[S42] C++：继承与虚函数
来源：http://dali.yonumen.top/Article/details/gtgoxmqrla.html

class B : public Base { public: void f() override {} };
来源：http://dali.yanxiufei.cn/Article/details/gtdtxrzfip.html

[S43] C++：智能指针
来源：http://dali.ehwqpu.com/Article/details/gtgdjigglc.html

auto p = std::make_unique<int>(5);
来源：http://dali.ppjwa.cn/Article/details/gtfcffytzy.html

[S44] C++：引用传参
来源：http://dali.zhiwuduotai.top/Article/details/gtdhxxyxpm.html

void inc(int &x) { ++x; }
来源：http://dali.tian-w.cn/Article/details/gtbxfjrroa.html

[S45] C++：lambda
来源：http://dali.yuxming.cn/Article/details/gtfyazudox.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fengsongda.top/Article/details/gtiuhquwwg.html

[S46] C++：函数模板
来源：http://dali.gogol.net.cn/Article/details/gtfsceqmfa.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jyoumei.cn/Article/details/gtpzetbjid.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhongyouzk.top/Article/details/gtjopmevkr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cdnleiting.top/Article/details/gtsbgpwbyg.html

[S48] C++：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtymfwkewo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenjidiqi.icu/Article/details/gtixlyjmss.html

while (std::getline(in, line)) { }
来源：http://dali.xziqi.cn/Article/details/gtibecwayk.html

[S49] C++：写文件
来源：http://dali.yvedp.cn/Article/details/gtidvsvvwy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.daria6918.cn/Article/details/gtetxmyynl.html

[S50] C++：格式化数字
来源：http://dali.yuanzhike.top/Article/details/gtawpdwelm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cashguo.top/Article/details/gtjebfgweg.html

[S51] C++：显式类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrreearau.html

static_cast<double>(a) / b
来源：http://dali.jlsjyb.cn/Article/details/gtaeczdlvl.html

[S52] C++：const 与 noexcept
来源：http://dali.daria6918.cn/Article/details/gtkzxqkwul.html

int size() const noexcept { return n_; }
来源：http://dali.snrcjt.cn/Article/details/gtredgures.html

[S53] C++：移动语义
来源：http://dali.cucudq.cn/Article/details/gtqzntrtrh.html

std::vector<int> w = std::move(v);
来源：http://dali.yj202588.top/Article/details/gthdgzaxri.html

[S54] C++：异常处理
来源：http://dali.chenzaomai.com/Article/details/gtqycngpdi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpevcexzh.html

[S55] C++：结构化绑定
来源：http://dali.shzxlz.cn/Article/details/gthwvetzoh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daxiang520.top/Article/details/gtzrxexqwj.html

[S56] C++：optional
来源：http://dali.pengpengdd.cyou/Article/details/gtgbrgqqae.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yueranfly.top/Article/details/gtlycmxfqr.html

[S57] C++：编译期常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrohhyipu.html

constexpr int N = 10;
来源：http://dali.xziqi.cn/Article/details/gtlrcfxkzx.html

[S58] C++：命名空间
来源：http://dali.gaohongyu789.top/Article/details/gtnstekjko.html

namespace ns { int f() { return 1; } }
来源：http://dali.yvedp.cn/Article/details/gtgjvtzvjg.html

[S59] C++：静态断言
来源：http://dali.yuxming.cn/Article/details/gtyqimzgqv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gtbkeaclzi.html

[S60] C++：遍历并删除元素
来源：http://dali.zhixingplan.top/Article/details/gttcchxbsj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gttivaqmlf.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtfwvaarwi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.svipenyu.cn/Article/details/gtidvledxf.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtclttopow.html

[T01] Kotlin：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtbsdhmvum.html

println("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtqjpexxtf.html

[T02] Kotlin：变量
来源：http://dali.jianghu66.top/Article/details/gtuivxgduo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnxiangtu.top/Article/details/gtuzxofgwb.html

[T03] Kotlin：字符串模板
来源：http://dali.hnxiangtu.top/Article/details/gtavabpgqm.html

"值: $b"
来源：http://dali.cashguo.top/Article/details/gtrxzkfkvh.html

[T04] Kotlin：空安全
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtisrvkj.html

val n: String? = null;  n?.length
来源：http://dali.aizwys.cn/Article/details/gtkrvaiuia.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258888.top/Article/details/gtxzemuyou.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sxryk.cn/Article/details/gtrlhcvlde.html

[T06] Kotlin：集合映射
来源：http://dali.nanxinkj.top/Article/details/gtsoujgote.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ehwqpu.com/Article/details/gttvjvqghl.html


<!-- 参考信息 -->